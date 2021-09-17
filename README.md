# Pizza_Ordering_System
A dialogue system with free conversation structure for ordering a pizza!

This pizza-ordering bot was developed by me and a classmate for the final project in our Dialogue Systems class. It asks the user questions about their order one at a time (i.e. "What size pizza would you like?") but the user is not limited by what the bot asks them--they can provide information about any aspects of the pizza in any order, which lets them update their order throughout the dialogue.  The bot uses a semantic frame which stores the order information, and is trained on annotated pizza ordering conversation data.  

The bot is built with Python and was developed in a Linux environment, and I have ported it to a Jupyter notebook and am now developing it in Google Colab.  Running the first code block will define most of the bot's functions, but most importantly it trains the bot using our training data.  It mounts to the Google Drive it is in so it can access the training files, so the filepath where you put the .ipynb file as well as the filepath to your training data folder must both be specified in this code block. 

The second code block starts the dialogue, so check out the menu file, place an order from the great (and fictitious) Tony's Pizzeria, and save me a slice!

Some of the features of the bot include:
  - free-input style
  - repeat and cancel functions
  - chitchat function - if nothing in your input can be inputted to the semantic frame, our bot replies in the style of the ELIZA bot
  - detect some common item misspellings

Some features that still need to be worked out/currently cause some issues:
  - ordering multiple pizzas, so just one at a time for now!
  - restart function gets a little weird
  - question-answering and recommendation-giving functions don't work fully yet

