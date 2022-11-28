# Validation and verification
## Terms
- Data integrity -> refers to the reliability of data in terms of its accuracy, completeness, and consistency over its lifecycle
- Data accuracy -> a term used to describe how valid or invalid the data is, or the processes used to make sure that the data stored is trustworthy

### Validation
- Validation -> Makes sure the data is sensible so it isn't obviously wrong
  - Improves accuracy but doesn't gurantee accuracy
- Data type check -> Checks that the value entered is of the required data type
- Range check -> Checks that the data is between an upper limit and a lower limit
- Limit check -> Used to check either the upper limit or the lower limit
- Length check -> Checks that a specific number of characters or digits has been entered
- Format check -> Used to check that the data is in a specified format
  - Regular expressions can be useful here to match a string against a pattern
- Presence check -> Checks that something has been entered into a field, and the field has not been left blank
- Existence check -> Used to check that a piece of data or the name of a file actually exists
- Uniqueness check -> Checks that a value entered is a new and original value
- Consistency check -> Checks that pieces of data from two or more fields are compatible with each other
- Check digit -> A digit that helps confirm that a code is correct

### Verification
- Verification -> making sure the data is accurate by checking it against a source
- Visual check -> a person checks that the data being entered from one document into another is the same
- Double entry -> requires a user to input the same information twice, into two separate fields, and the two values are then compared to check that they are the same

## Links
- Data structures

## Strengths
- Commonly help websites so users enter emails and passwords correctly so they aren't locked out of their account
- Ensures that data has been correctly entered everywhere

## Limitations
- Can make the code complicated the more validation is added
- Can take a while to implement and test every form of validation

## Summary
Validation and verifications are ways of preventing obvious mistakes and try to make data up to date and correct. 
One of many methods depending on the circumstances will help this to be achieved.
