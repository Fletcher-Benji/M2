# Milestone Project 2 

Brefi: I am to build an interactive front-end site. The site should respond to
the users' actions, allowing users to actively engage with data, alter the way the site
displays the information to achieve their preferred goals.

Project idea 2 'Memory Game'

I am to create a basic card mating memory game, using tarrot cards I have found online I am to create a user experiance with feedback and changes in the code to reflect the users actions.

So this means I need to create web app that has the functionality of:

1. Showing the score (how many cards matched)
2. The ability to match cards 
3. A graphic or promp to allow the user of any correct or incorrect actions
4. Congratulate the player, allowing for a satisfying experiance 

 
## UX
 
UX process

allow the “External user” to enjoy a basic JavaScript game, in a number of browsers


## Features

- 1 Basic HTML
- 2 Inline and External CSS
- 3 Score updater
- 4 Cards will change if matched
- 5 Website will promt when matched
- 6 Website will promt whem there is no match
- 7 congratulates user upon completeiion
- 8 JavaScript code
  * for loops (card array)
  * addEventListener (clicking event)
  * setAttribute (makes game board, changes card state, checks matches)
  * Sort 
  * math.random (random card placement each time)
- 9 Random cards generated 
 

### Features to Implement in future
- more matchable items
- custome uploadable icons  

## Technologies Used

HTML 5
CSS 3
JavaScript
Visual Studio Code 

## Testing

1. click card to show image:
    1. click the 'blank' image
    2. card now filpped 

2. match cards:
    1. highlight and click blank cards
    2. highlight and click another blank card that is the same as the first
    3. text promt "its a match!"

2. Cards reset to blank when not paired 
    1.  highlight and click blank cards
    2.  highlight and click another blank card that is the different as the first
    3. text promt "not a match."

3. score change 
    1. repeat testing 1 and succesfully match two sets of cards
    2. score chaned +1 for each pair  

4. Congratulations promt 
    1. match all cards
    2. texty promt "Congratulations! all the cards are found"

## Bug

-When clicking on three objects you can reveal a card while the If or Or statment is running, so as the match or no match promt is active you can reveal more cards.
If I where to revisit this I would ensure the user is limited on the imputs for a short period to ensure the code is used for its original purpose.

## Deployment

I will be hosting my project on Github for easy deployment/development onto an exsiting domain. Paired with heroku.
(I have had to add a PHP index file that just redirects top the index.html file, this is the only way I have found to deploy a static site to heroku)

### Media
Vintage Tarot cards 

