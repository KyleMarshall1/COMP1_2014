#Task Sheet 1
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



#Task Sheet 2
1.
2. The DisplayMenu() function
3. The GetRank(RankNo) function

#Additional Task 1
1. Fixed value - Cannot be changed after set for example the length of an array 
   Stepper - Goes through a set of values in an organised way e.g. 'count'
   Most recent holder - Only holds the most latest input. AceRAnk
   Most wanted holder - Holds the value the user wants e.g. If the user wants the highest number, it will hold the highest number. Not a smaller number if one is encountered
   Gatherer - 
   Transformation - A variable that always gets a new value from a calculation of other variables  
   Follower - 
   Temporary - Holds a value for a short time only. 

2. Called by reference means that the variable inside the function uses the same memory location as the variable passed as the parameter whereas called by value means that the function copies the variable to the parameter.
   
>>>>>>> 42c10a1308ca8fe2df38bb886e1c4235f9a7758c
