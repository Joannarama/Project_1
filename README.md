



# Fixes

## index.html
**Error:** Statement h3 not allowed as child of element span in this context. (Suppressing further errors from this subtree.)
**Solution:** Change span to div.

**Error:** An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.
**Solution:** alt attribute added to the image to resolve this error. 

Error: Attribute alt not allowed on element a at this point.
Solution: I removed the alt attribute which caused the error.

Error: No p element in scope but a p end tag seen.
Solution: I had placed a h tag withing the p tag. This caused the error and removing the p tag resolved the issue. 

## services.html
Error: An img element must have an alt attribute, except under certain conditions.
Solution: alt attribute added to the image to resolve this error.

Error: No p element in scope but a p end tag seen.
Solution: I had placed a h tag withing the p tag. This caused the error and removing the p tag resolved the issue. 

## contact.html
No errors

## CSS
1 Error found:
File not found: https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400,600&display=swap: Bad Request
I am using the suggest @import approach and this is breaking the validation. I do not know how to fix.