#Use pdfcrop to cut multiple files and save as the same names

```
 #!/bin/bash
 for FILE in ./Transition2*/*/*.pdf; do # File locations
     pdfcrop "${FILE}" "${FILE}"
 done
 ```
