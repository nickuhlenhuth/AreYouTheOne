# AreYouTheOne

IMPORTANT: Please use the latest version of this code. The was an issue inserted about two weeks ago, which has now been fixed!

 Are You The One? Code
 
 NEW FEATURE: Blackout odds and Beam probabilities. Before the number of lights are revealed, put the current week's guesses into the currentWeek variable and run the code. It will print out the blackout odds and the liklihood of each beam count.
 
 
 After Week 7, this code was able to determine the winning matching for Season 3!
 
 Calculates the likelihoods of each couple being a perfect match (assuming all matches are equally likely).
 
 IMPORTANT:
 - Each week, update the weeks choices and number of matches (as well as the allWeeks list!).
 - Each week, update the truth booth information.

 The 'load_from_file' boolean specifies whether the matches should be loaded from the match file
 For the first time you run, make sure this is set to False (unless you have the allmatches.p file already!)
 Then you can change it to True in order to run faster.
 load_from_file = False
