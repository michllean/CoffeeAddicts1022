# CoffeeAddicts1022

**Team Name:** Coffee Addicts

**Members:** Hanbyul Kim, Hyein (Michelle) An,  Tayseer Abdelaziz

**Emails:** mimi0812@my.yorku.ca, hyein@my.yorku.ca, tayseer7@my.yorku.ca

**Game Name:** Random Number Memorization

**Description:**
The system will generate a random set of numbers, and display them one after another. The user must memorize the numbers, and compare the number currently displayed on the screen with the number that was displayed several turns before the current number. The user gets to decide the number of turns. There are: 2-turns back, 3-turns back, 4-turns back, and 5-turns back. If the numbers are equal, then the user presses ‘O’ symbol. If the numbers are not equal, presses the ‘X’ symbol. For example, if the numbers displayed are 2, 6, 7, 6, for 2-turns back mode, then the correct answer is ‘O' because 6 and 6 are equal. However, if the numbers displayed are 3, 1, 6, 5, 7, 2, 4, for 5-turns back mode, the correct answer is ‘X’ since 4 and 1 do not match. If the user presses the wrong symbol, the game will notify the loss of the user and stop the game. Otherwise, the system will continue to generate and display a new number. This will repeat until the user either win or lose. For the win, user must make 25 correct selections. However, if user selects the wrong symbol, or be timed-out(3seconds) the system will notify the loss of the user and end the game.  
(Changes to project description made and allowed by TA Miodrag Tasic) 

**Features:**

**Requirements:**
1. The game should be available through android (mobile) devices. This game will be supported in both portrait mode and landscape mode. i.e., its view will not be absolute(fixed), but rather be relative depending on the type of device (sizes) used. 

2. Once ‘Start’ button is clicked, the screen then will display 4 buttons, ‘2-turns back’, ‘3-turns back’, ‘4-turns back’ and ‘5-turns back’. These corresponds to the level of difficulty, from easy to hard respectively.  

3. There will be an ‘help’ button in the top right corner of the screen. Once pressed, it will display the instruction on how to play the game.  

4. Once the mode is selected, the system will display the very first number that has been randomly generated. It will be displayed for 3 seconds and fade out. 
4-1. Once the number fade out, the system will display another randomly generated number. 

5. The user must compare the most recently displayed number to the number that was displayed several turns before the recent number. The number of turns here are the turns that was first selected in the main screen. For example, if ‘3-turns back’ mode is selected, the user must compare the most recently displayed number to the number that was displayed 3 turns before the recent number.  

6. The screen will display ‘X’ and ‘O’ symbol in color red and green respectively, on the bottom of the screen. If the compared numbers match(i.e., are equal), user must click on the ‘O’ symbol. If they do not match(i.e., are not equal), then user must click on the ‘X’ symbol.  

7. Once the correct symbol is selected, next number is displayed on the screen, and this is repeated until the user either wins or loses.  
7-1. For the win, user must make 25 correct selections in a row regardless of the difficulty mode he or she chooses. 
7-2. If user selects the wrong symbol, or fails to select a symbol within the first 3 seconds after the number is displayed, the system will notify the loss of the user and end the system. 

8. When a round is over, the system will display the difficulty selection page to the user. (Refer to the requirement #2) 

9. The font size of the displayed numbers will be large, and be in the centre of the screen. 

10. The game will contain no other games asides of green and red(for the ‘O’ and ‘X’ symbol) so that the numbers and symbol stand out more to the users.  
