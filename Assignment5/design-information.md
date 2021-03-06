## Design Information Document
# Ethan Wu CS6300 Assignment 5

1) I added class ?User? with the items: username, major, seniority, and email. This ?User? class can do the following actions: ?Login? and ?Register?. ?Login? includes items ?username? because that is requirement to perform this action. I also included a Boolean validation method in order to interact with a ?Device? class which I included to store all the ?Student Accounts? class which I have also included. ?Register? includes the method isRegistered to check to see if the account has been registered already.
2) An additional ?Quiz? class was added with the following actions: ?Add?. ?Remove?, ?Practice?, and ?View Statistics?. A solid line was draw between the ?User? class and ?Quiz? class with dotted lines connecting to the solid for ?Add?, ?Remove?, ?Practice?, ?View Statistics?.
3) ?Add? action includes many requirements which we added as the following items: name, description, numOfWords, numOfIncorrect, words, definitions. Method addQuiz() was added to perform this action.
4) ?Remove? requires one item: name and we added method removeQuiz() to perform this action.
5) Since users must select the name of quiz from a list I added an item: name to the ?Quiz? class. 
6) ?Practice? requires the following items: numOfWords, numOfIncorrect, words, definition, response, score, dateTaken, and timeTaken. From the description we can see that date and time are important factors so we created utility classes ?Date? and ?Time? as well as ?Date Taken? with method getDate() and ?Time Taken? with method getTime().
7) Quiz statistics is not exactly a quiz but it is associated with the ?Quiz? class so I created a separate class called ?Statistics?. To satisfy the requirements, I added the following items to ?View Statistics? action class: score, firstUser, secondUser, thirdUser (for the first three to score 100%), name, dateTaken, timeTaken. Method viewStats() was added to perform this action.
8) User interface responsiveness and intuitive relates to UI elements and not represented in class diagram. 
9) Performance of game is also related to execution and writing efficient code and is not represented in the class diagram. 


