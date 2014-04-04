#Task 3

1. The function that needs to be updated is the GetPlayerName()
2. To make sure they are repeatedly asked I will add a while loop into the function
3. I will add a variable called ValidName, it will be boolean

	ValidName: Boolean
	PlayerName: String
	FUNCTION GetPlayerName()
		OUTPUT ""
		ValidName <- False
		WHILE not ValidName
			OUTPUT "Please enter your name: "
			INPUT PlayerName
			IF PlayerName = ""
				OUTPUT "You must enter something for your name! "
			ELSE
				ValidName <- True
			END IF
		END WHILE
		OUTPUT ""
		RETURN PlayerName
	END FUNCTION

##3b
1. The function responsible for adding scores to the table is the UpdateRecentScores function
	