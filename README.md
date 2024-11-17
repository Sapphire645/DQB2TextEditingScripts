# DQB2TextEditingScripts
Future scripts for text and cutscene editing.



## CURRENT PROGRESS:

It seems the cutscene data is stored in chunks of 0x34 entries:
- The value at 0x2E to 0x30 indicates the action the entry will perform.
- The values 0x00-0x04, 0x04-0x08, 0x08-0xC .... are the arguments of the action. What they mean depend on the action. If they are empty they are stored as 0xFFFF... 

My current script is taking those action flags and converting them to some sort of "pseudo-code" that will allow you to edit cutscenes and read cutscenes more intuitively.
Here's how it's looking as of now:

![IMAGE](https://github.com/Sapphire645/DQB2TextEditingScripts/blob/main/PROGRESS/PROGRESS.png)

The rows marked as *: are the ones I have not figured out the function structure to yet


Hopefully I'll be able to release an intuitive cutscene editor script in the future!
