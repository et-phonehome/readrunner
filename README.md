# readrunner

_Speed reading. Use this one weird trick to read quicker!_

<img src="https://i.imgur.com/WgkSzND.png"
     alt="Demo Screenshot"
     style="float: left; margin-right: 10px;" />

*^ Finished product ^*
_____________________________________
## Inspiration
Our inspiration for this project stems from our interest in Rapid Serial Visual Presentation (RSVP) and its application to speed reading. The goal of RSVP is to enhance reading comprehension and decrease visual fatigue by quickly displaying words or a group of words in sequential order on a screen. This method minimizes eye movements and blinking while reading, increasing the readers' attentional focus.

Some people have found great success using RSVP, increasing their reading speed from a usual average of about 150 words per minute to over 700+ words per minute with sufficient training. (Crazy, right?) Therefore, due to its potential for success, our goal was to create a program that could replicate this method of reading enhancement.

## How we built it
We built ReadRunner all with Python 3 on Jupyter notebook because we all have experience using it in our coursework and wanted to expand the capabilities of Jupyter Notebook beyond what we were doing in class.

We used the newspaper library to scrape the text from articles that we inputted into our program and then we parsed through this text to make the color of the middle letter red. This middle letter is colored red so that the reader's focus is solely on the middle of the display and they use their peripheral vision to read the words as they come.

We displayed the words one at a time at a certain word per minute rate using Matplotlib and created an MP4 video that we could export and download into any of our devices.

## How to use
Launch _ReadRunner Playground_ as a Jupyter notebook (Python 3). Run the first fall to launch the user interface:

1. Type in a link to an article you'd like to read.
2. Type in your desired words per minute.
3. Begin reading faster than you've read before!



<img src="https://i.imgur.com/2srzFp3.png"
     alt="Demo Screenshot"
     style="float: left; margin-right: 10px;" />
_Tip: begin around 100-150 WPM. You'll find yourself increasing speed pretty quickly from there._


_____________________________________
### HackDarmouth V, 2019
### Created by Mohib Jafri, Evan Thompson, and Hiromu Ryan Rose
