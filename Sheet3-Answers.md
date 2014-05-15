#Task Sheet 3

##Task 12

###Questions

1. It should be kept globally

2. IsNextCardHigher() and OptionsMenu()

3. NextCard.Rank

4. The new option will have to be added to DisplayOptions(). If the user inputs '2', run the new function SetSameScore().

###Pseudo-Code

OUTPUT("Do you want the next card to have the same or lower value as the current card?: ")
INPUT LowerValue
LowerValue = LowerValue[0].Upper
WHILE LowerValue <> 'S' and LowerValue <> 'L' THEN DO
	OUTPUT ("Please enter a legit value "Same / Lower":")
	INPUTLowerValue
global SameCardLower
IF LowerValue == 'S' THEN DO
	global SameCardLower == False
ELIF LowerValue == 'L' THEN DO
	global SameCardLower == True