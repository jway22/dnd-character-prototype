# DnD Character Generator Prototype

For a coding exercise, I wanted to make a random character generator for Dungeons and Dragons.
As a dungeon master, I frequently need multiple characters to run the campaign.
This project is a way to quickly create characters with stats.

I wanted to start simple by including three races, the standard fantasy human, elf, dwarf,
and three classes, a fighter, rogue, and wizard. I also wanted the program to have the option to randomly select for the user.

The program itself creates a new Character class when initialized. It randomly "rolls four 6 sided dice", drops the lowest score,
and adds the remaining rolls. It does this a total of six times for each character stat.
Based on the class chosen (or randomized) it then assigns the rolls from lowest to highest, starting with the
least applicable stat to the most used stat for the class.
After the rolls have been assigned to a stat, the program then takes the character race and adds a stat bonus given by the race
and applies it to the correct stat roll.
Finally, the program assigns the correct stat modifier based on the stat total and displays the information in a basic generated table.

The continuation of this project will include adding in the rest of the standard races and classes from the Dungeons & Dragons Player's Handbook
along with hopefully creating a more visually pleasing interface.
