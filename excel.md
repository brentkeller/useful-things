# Excel Tips and Tricks


## Formulas

### Conditional output based on whether a cell contains searched text within
The following will output "Yes" if the target cell contains the string "Text" anywhere in it's value, otherwise the output will be "No"  
`=if(isnumber(search("Text",C2)),"Yes","No")`
