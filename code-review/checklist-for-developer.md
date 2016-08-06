## Checklist for Developer

Checklist Developer's should maintain before sending sending code for review.

- My code compiles	
- My code has been developer-tested and includes unit tests
- My code includes docs and comments where appropriate	
- My code is tidy (indentation, line length, no commented-out code, no spelling mistakes, etc)	
- I have considered proper use of exceptions	
- I have made appropriate use of logging	
- I have eliminated unused imports
- I have eliminated all warnings by code linter	
- The code follows the Coding Standards.
- Are there any leftover stubs or test routines in the code?	
- Are there any hardcoded, development only things still in the code?	
- Was performance considered?
- Was security considered?
- Does the code release resources? (HTTP connections, DB connection, files, etc)	
- Corner cases well documented or any workaround for a known limitation of the frameworks
- Can any code be replaced by calls to external reusable components or library functions?	
- Thread safety and possible deadlocks


