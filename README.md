# Audio to Text generator

## A Python script to convert large video files to text files by recognising speech
### Steps it performs:
1. Converts video file to audio file
2. Breaks the converted audio file into chunks based on minimum silence time(default 0.5 secs) between two words and minimum silence sound(deafult 16dBps) which determines the chunks breaking size and stores them in a audio_chunks folder.
3. The script then reads the chunks created and tries to recognise the speech using Google API.
4. Prints the text into the terminal file for each chunk.
5. Finally the recognised text id ready!!
