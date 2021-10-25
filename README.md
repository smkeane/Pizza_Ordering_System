# Pizza_Ordering_System
A dialogue system with free conversation structure for ordering a pizza!

This pizza-ordering bot was developed by me and a classmate for the final project in our Dialogue Systems class. It asks the user questions about their order one at a time (i.e. "What size pizza would you like?") but the user is not limited by what the bot asks them--they can provide information about any aspects of the pizza in any order, which lets them update their order throughout the dialogue.  The bot uses a semantic frame which stores the order information, and is trained on annotated pizza ordering conversation data.  

The bot is built with Python and was developed in a Linux environment, and I have ported it to a Jupyter notebook and am now developing it in Visual Studio Code.  Running the first two code blocks will define most of the bot's functions, and train the bot using our training data.   

The third code block starts the dialogue, so check out the menu file (created thanks to canva.com), place an order from the great (and fictitious) Tony's Pizzeria, and save me a slice!

Some of the features of the bot include:
  - free-input style
  - repeat and cancel functions
  - chitchat function - if nothing in your input can be inputted to the semantic frame, our bot replies in the style of the ELIZA bot
  - detect some common item misspellings

Some features that still need to be worked out/currently cause some issues:
  - ordering multiple pizzas, so just one at a time for now!
  - restart function gets a little weird
  - question-answering and recommendation-giving functions don't work fully yet
  - asking for pepperoni as a topping will override the pizza type (i.e. hawaiian pizza with pepperoni => pepperoni pizza with pepperoni)
 

