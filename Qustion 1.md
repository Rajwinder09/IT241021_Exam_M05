## Q1A_Formulas_Not_Calculating_Questions

## A. Key Questions to Ask the Uasers:
When troubleshooting this issue, it is essential to gather the right informtion. 

Some useful questions include:

#Is Excel set to manual calculation mode instead of automatic?
#Are the affected cells formatted as text instead of number of general format?
#Did you enter the formula correctly?ensuring that formula starts with (=)
#Is there any unnecessary apostrophe symbol before formula.

following is the link below:
(https://support.microsoft.com/en-us/excel)

## B. Common Troubleshooting technics in excel:
If the formulas are not calculating correctly, these steps can resolve the issue:

#Check Calculation Mode: Be ensure that it is set to 'Automatic' under Formulas of the calculation options
#Press F9: This will force Excel to recalculate formulas manually.
#Remove Leading Apostrophes: Sometime in the formulas bar some unnessary symbols and apostrophes appear which also create a lot problem.
#Check for circular Refrences: These can cause formulas to stop calculating. Excel usually alerts users if circular references exist.

## C: Common Excel Mistakes: 
Through research, some of the most frequent mistakes that cause formula errors include:

#Entering formulas as plain text: If a cell is formatted as 'Text'Excel would not recognize it as a formula.
#Forgetting to use the = sign: Typing SUM(A1:A10) instead of =SUM(A1:A10) will not work.
#incorrect use of absolute vs. relative references:$A$1 keeps a references fixed, while A1 is relative. incorrect use can break calculations when copying formulas.

## D: Additional Issues to investigate:
After addressing the above points, other potential problems might include:

#Are there macros running that overide calculations?
Macros written in vba can prevent formulas from updating.
#Are there any third-party add-ins interfering with excel?
Some excel add-ins modify calculation behaviour. The user can disable them under File > Options > Add ins.





