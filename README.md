# Project: Date
## Description
[ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) is an international standard covering the worldwide exchange and communication of date and time-related data. The standard uses the [Gregorian calendar](https://en.wikipedia.org/wiki/Gregorian_calendar). Calendar date representations are in the form YYYY-MM-DD (or YYYYMMDD).
In this project you will write a java class that validates and processes calendar dates in accordance to the ISO 8601 standard.
## Specifications
In `Date.java` do the following:
- Complete the `isValid` method so that it returns true if the given date is valid, other wise return false.
- Complete the `toString` method so that it returns a string in the YYYY-MM-DD format if the given date is valid. Otherwise, return `"invalid"`. For example, `toString(2024, 7, 4)` returns `"2024-07-04` and `toString(2023,2,29)` returns `"invalid"`.
- Complete the `monthString` method so that it returns a string that represents the given month in an abbreviated form, if the given month is valid. Otherwise, return `"invalid"`. For example, `monthString(6)` returns `"JUNE"` and `monthString(0)` returns `"invalid"`.

In `DateTest.java` do the following in the `main` method:
- Thoroughly test each method to verify that it works correctly. For example,
  -  `isValid(2024,13,40) == false`
  -  `toString(2024,2,29).equals("2024-02-29")`
## Coding Standards
1. Adhere to the specifications
2. Use meaningful identifiers.
3. Remove comments generated by an IDE.
4. Use JavaDoc to completely document your code. Include a description of your program and acknowledge yourself as the author using the `@author` tag.
5. Any output should be user-friendly.
6. Your code must be well-organized, easy to read, and properly formatted.
## Submission
Submit `Date.java` and `DateTest.java`
