# YouTube-Automation

Basic aim of creating this project is to create videos from the text data using python code. I came to this idea while discussing with my friends,one can do many interesting 
things with few lines of python code and i choose to start with a simple video generating tool using python.

The project is broken down into multiple steps:

1. Load the Scraped dataset of MCQ (multiple choice questions) with option and detail answer in csv format.
2. Generate two images for each row (or question) and save in sequence.
  * First one is for question with options.
  * Second one is for questions with highlighted and detailed answer
3. Finally merge this frame according to your convenience.


## Libraries
* Pandas
* Numpy
* PIL
* os
* textwrap
* shutil
* pydub
* ffmpeg

## Programming language 

* Python
