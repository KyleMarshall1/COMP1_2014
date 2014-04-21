#Task 3

<<<<<<< HEAD
1. GetPlayerName()
2. Add a while loop
3. ValidName, will be boolean
=======
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

##5
1. datetime module
2. DisplayRecentScore, UpdateRecentScore,ResetRecentScore and PlayGame?
3. To display a datetime object you must convert it to a string using strftime().
	
>>>>>>> 42c10a1308ca8fe2df38bb886e1c4235f9a7758c
