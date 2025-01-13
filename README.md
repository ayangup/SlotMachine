## Slot Machine Game ##

#Overview
The Slot Machine game is a fun, interactive Python-based terminal application that emulates a slot machine. 
Users can deposit money, choose the number of lines to bet on, place bets, and spin the slot machine reels 
to test their luck. With randomized outcomes and payouts, the game ensures an engaging experience.

#Features
- Deposit System: Add funds to your account to start playing.
- Betting Options: Choose the number of lines to bet on (up to 3) and specify your bet amount within customizable limits.
- Slot Machine Spin: A randomized slot machine generates symbols across rows and columns.
- Winnings Calculation: Based on matching symbols and their values, winnings are calculated and added to your balance.
- User-Friendly Interface: Clear prompts guide users through depositing, betting, spinning, and checking results.

#Rules
1. Players deposit funds before starting.
2. Choose up to 3 lines to bet on.
3. Place bets for each line, within the defined betting range ($1 to $100).
4. Spin the slot machine:
  -If symbols match across a line, you win according to the symbol's value.
  -Winnings are added to your balance, and total bets are subtracted.
5. Continue playing until you decide to quit or run out of funds.
   
#Symbol Details
Symbol |	Count (per reel) |	Value (per line match)
  A    |        	2	       |           $5
  B	   |          4	       |           $4
  C	   |          6	       |           $3
  D	   |          8	       |           $2

#How to Play
1. Run the Game: Execute the script in a Python environment.
2. Deposit Money: Enter an amount to add to your balance.
3. Choose Lines: Specify the number of lines to bet on (1-3).
4. Place Your Bet: Enter your desired bet amount for each line.
5. Spin the Reels: Watch the slot machine generate symbols and see if you win!
6. Check Your Winnings: Review your winnings and updated balance after each spin.
7. Exit or Continue: Press "e" to exit or hit Enter to keep playing.
   
#Technical Details
- Programming Language: Python 3.x
- Modules Used: random for generating randomized slot machine outcomes.

#Disclaimer
This project is provided "as is" without any guarantees or warranties of any kind, either express or implied, 
including but not limited to fitness for a particular purpose, merchantability, or non-infringement. The author 
assumes no responsibility for errors, inaccuracies, or omissions in the code or documentation.

#By using this project, you acknowledge that:
- You are solely responsible for any modifications, adaptations, or usage of the code.
- The project is intended for personal, educational, or demonstration purposes only and should not be used in real-world gambling or financial applications.
- The author is not liable for any direct, indirect, incidental, or consequential damages resulting from the use or inability to use the project.
- Always ensure you understand the code and its implications before integrating or deploying it in any environment.
