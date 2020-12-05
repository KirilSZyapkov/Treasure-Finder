# Treasure-Finder

Write a function that decrypts a message by a given key and gathers information about hidden treasure type and its coordinates. On the first line you will receive a key (sequence of numbers).  

On the next few lines until you receive "find" you will get lines of strings. You have to loop through every string and decrease the ascii code of each character with a corresponding number of the key sequence. The way you choose a key number from the sequence is just looping through it. If the length of the key sequence is less than the string sequence, you start looping from the beginning of the key. For more clarification see the example below. After decrypting the message you will get a type of treasure and its coordinates. The type will be between the symbol '&' and the coordinates will be between the symbols '<' and '>'. For each line print the type and the coordinates.
