Instructions
Manage a game player's High Score list.

Your task is to build a high-score component of the classic Frogger game, one of the highest selling and most addictive games of all time, and a classic of the arcade era. Your task is to write methods that return the highest score from the list, the last added score and the three highest scores.

The functions in this exercise accept an array containing one or more numbers, each representing one 'game score'.

The player's game scores can be read from

scores
scores[0]
scores[1]
...
scores[scores_len - 1]
personal_top_three() should write the player's top scores to

output
output[0]
...

LEARNING

size_t is a special unsigned integer data type defined in the standard library <stddef.h>

On different computers, the amount of memory available varies.
On an old 16-bit system, an int might only handle numbers up to 32,767.
On a 64-bit system, memory addresses are much larger.

If you used a standard int to count the elements in a massive array, you might "run out of numbers" (integer overflow) before you finished counting the array. size_t is "platform-dependent," meaning the compiler automatically makes it the perfect size for the hardware you are using.
