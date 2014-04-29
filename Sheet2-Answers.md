#Task Sheet 2

##Task 6

###Questions

1. Ace High should be set globally so it doesn't have to be changed after each game

2. DisplayMenu()

3. LoadDeck()

###Pseudo Code

FUNCTION DisplayOptions()
	OUTPUT("5. Options")

FUNCTION GetOptionChoice()
	IF  Choice = '5' THEN
		FUNCTION SetOptions(OptionChoice)


FUNCTION SetOptions(OptionChoice)
	OUTPUT('1. Ace High / Ace Low")
	OUTPUT(" Enter your option choice ")
	INPUT OptionChoice
	IF OptionCHoice = '1' THEN
		FUNCTION SetAceHighOrLow()

FUNCTION SetAceHighOrLow()
	OUTPUT ("Do you want to set Ace (H)igh or (L)ow?: ")
	INPUT AceHighChoice
	IF AceHighChoice = 'H' THEN
		ACEHIGH <-- True
	RETURN ACEHIGH
	
## Task 7

###Pseudo-Code

FUNCTION BubbleSortScores(RecentScores)
	Swapped <-- TRUE
	listlength <-- LENGTH(RecentScores
	WHILE Swapped DO
		Swapped <-- False
		FOR count in range (Listlength) DO
			IF RecentScores[count].Score > RecentScores[count +1].Score DO
				temp <-- Recent Scores[count]
				RecentScores[count].Score <-- RecentScores[count +1].Score
				RecentScores[count +1].Score <-- temp
				Swapped <-- TRUE
		RETURN RecentScores

		
