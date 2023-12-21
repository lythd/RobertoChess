# RobertoChessBot
A Chess Bot I made for Sebatian Lague's chess bot competition. It placed 293th out of 624 total bots, so top 50% woo!

Competition Github (if you want to run the bot come here and use the bot as MyBot.cs): https://github.com/SebLague/Chess-Challenge

Competition Video: https://youtu.be/iScy18pVR58

Results Video: https://youtu.be/Ne40a5LkK6A

## Explanation
I wanted to have fun with this, so I made the eval function inspired by an rpg. It rates positions based on 5 stats, hp (how many pieces are there, aka how many hits it can take), attack (how many attacks are possible), defense (how many pieces are being defended), speed (how many squares can be traveled to), and dexterity (how many squares could be traveled to if there was no other pieces). I hope you like this presumably unique idea, even if it might not perform as well as if I included standard piece values. More info is in the comments of my code.

I hope you all like it!

## How to use
Whichever bot you want to use, rename its My Bot folder to just "My Bot", if you want to use any of the bots as the Evil Bot (opponent to test out the other on) rename its Evil Bot folder to just "Evil Bot". Do not mix up the folders as an Evil Bot folder cannot act as My Bot and vice versa, if you ever forget which type it is just check the name of the .cs file inside. For comparison I have included the template MyBot and EvilBot's from Sebastian, as well as BoyChesser the winner of the competition.

## Changelog

# v0.1
- Added basic minimax search
- Basic evaluation algorithm (the hp attack defense speed scoring system thats quite unique to this bot)
