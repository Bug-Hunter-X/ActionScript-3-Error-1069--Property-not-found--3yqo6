# ActionScript 3 Error 1069: Property not found

This repository demonstrates a common ActionScript 3 error: Error #1069: Property not found.  This error occurs when attempting to access a property of an object that is null or undefined. The example shows how to handle this error using null checks before accessing the object's properties. The corrected version provides robust null checking to prevent the error.

## Bug Report
The original code assumes that the object 'myObject' always exists and has the 'someProperty' attribute.  If myObject is null or undefined, it throws an error 1069. 

## Solution
The solution involves adding a null check before accessing 'someProperty'. This ensures that the code only attempts to access the property if the object is valid.