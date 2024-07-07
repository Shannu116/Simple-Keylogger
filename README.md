# PRODIGY-CS-4
A simple keylogger

1.  Keylogger Class: 
   - The `Keylogger` class is defined to handle keylogging functionality.
   - It initializes an empty log to store pressed keys.

2.  Methods: 
   - `append_to_log(string)`: Appends the given string (representing a key) to the log.
   - `process_key_press(key)`: Processes key presses. If the key is a character, it converts it to a string. If it's a special key (like space), it handles it accordingly.
   - `report()`: Prints the accumulated log and resets it. It also schedules itself to run every 5 seconds.
   - `start()`: Sets up a keyboard listener using the `pynput` library. It starts listening for key presses and calls the `report()` method.

3.  Usage: 
   - both 'keylogger.py' and 'key_logger_start' both files should be in same folder because to run key_logger_start module keylogger is important there is no inbuilt module in python
   - to start the keylogger run the key_logger_start.py file then for every 5 seconds, the log's of key stocks will we appeared in the output panel 


Remember to handle the security implications of keylogging carefully, as it can be misused. Ensure that you have proper authorization and legitimate use cases when implementing such functionality.
