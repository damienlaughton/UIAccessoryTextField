# UIAccessoryTextField
A Swift text field which is an alternative to drop down options

# Controlling Behaviour
UIAccessoryTextField exposes public variables for controlling behaviour.
 
# autoCompleteStrings
 
myAutoCompletetextField.autoCompleteStrings = ["MK10 0AB", "W1T 3NQ"]

default is .none

The text field will add a non standard input accessory view with only those strings

# shouldHighlightFilter

myAutoCompletetextField.shouldHighlightFilter = true

default is false

Strings which are filtering true have the highlight in bold

# testPrefixOnly
 
myAutoCompletetextField.testPrefixOnly = true

default is false

Filtering is done on the prefix of the string

# cellStyle
   
myAutoCompletetextField.cellStyle = .wideTwoLine

default is .normalOneLine

Two styles of cell for you to get started with

 
