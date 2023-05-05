Download Link: https://assignmentchef.com/product/solved-csi2372-assignment-1
<br>









Question 1 of 2) <strong>Life Predictor  </strong>




The Social Security Administration maintains an actuarial life table that contains the probability that a person in the United States will die (<a href="https://www.ssa.gov/OACT/STATS/table4c6.html">http://www.ssa.gov/OACT/STATS/table4c6.html</a><a href="https://www.ssa.gov/OACT/STATS/table4c6.html">)</a>. The death probabilities for 2009 are stored in the file <sub>LifeDeathProbability.txt</sub>  which is available in the Assignment 1 files.  In this file, there are three values for each row: the age, death probability for a male, and death probability for a female.  For example, the first five lines are:




<ul>

 <li>006990 0.005728</li>

 <li>000447 0.000373</li>

 <li>000301 0.000241</li>

 <li>000233 0.000186</li>

 <li>000177 0.000150</li>

</ul>




The interpretation for the fourth line is that a 3-year-old female has a 0.000186 chance of dying during.




Write a program that inputs an age and sex from the keyboard in the main function. The main function should call a function named <sub>simulate</sub> (that you must write), sending in the age and sex as parameters. The function should simulate to what age a person will live by starting with the death probability for the given age and sex. You can do this by reading the data from the file row by row. Skip rows that are less than the input age. Once the input age is reached, generate a random number between 0-1 and if this number is less than or equal to the corresponding death probability then predict that the person will live to the current age and return that age.  If the random number is greater than the death probability then increase the age by one and repeat the calculation for the next row in the file.




If the simulation reaches age 120, then stop and predict that the user will live to 120. The main function should output the simulated age for when the person will die. This program is merely a simulation and will give different results each time it is run, assuming you change the seed for the random number generator.


































Question 2 of 2) <strong>High Score Manager</strong>




Write a program that manages a list of up to 10 players and their high scores in the computer’s memory (not on disk as files). Use two arrays to manage the list. One array should store the player’s name and the other array should store the player’s high score. Use the index of the arrays to correlate the name with the score. Do not use a struct or class for this program. Your program should support the following features:




<ol>

 <li><strong>Add</strong> a new player and score (up to maximum of 10 players).</li>

 <li><strong>Print</strong> all players and their score to the screen</li>

 <li>Allow the user to enter a player name and output that player’s score or a message if the player’s name has not been entered (i.e., <strong>search</strong> a player’s name)</li>

 <li>Allow the user to enter a player name and <strong>remove</strong> the player from the list</li>

</ol>




Create a menu system that allows the user to select which option to invoke. The features must be in forms of functions.














