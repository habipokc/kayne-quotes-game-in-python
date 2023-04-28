# kayne-quotes-game-in-python

This is a simple Python program that uses the Tkinter module to create a GUI application that displays random Kanye West quotes fetched from the "https://api.kanye.rest" API. The program also includes two images (background.png and kanye.png) that are used as the background of the canvas and the button that fetches new quotes, respectively.

The main logic of the program is contained in the get_quote() function, which sends an HTTP GET request to the API and extracts the quote from the JSON response. The canvas object is then updated with the new quote using the itemconfig() method of the canvas widget.

To run the program, simply execute the kanye_quotes.py script. When the GUI window appears, click the button with Kanye's face to fetch a new quote.
