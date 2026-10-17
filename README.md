# lecture-13-

1.THE DATE,AND THE TWO TOOLS YOU MET:
17 oct 2026 
tools used - 1.ffmpeg  2.qrencode


2.WHAT EACH ONE IS FOR:
ffmpeg - used for converting videos into jpg and gif.

qrencode - used for converting url into qr code.


3.THE COMMANDS THAT WORKED:

commands for ffmpeg :-

ffmpeg -i nature.mp4 nature.jpg  OR 
ffmpeg -i nature.mp4 -vframes a.jpg (to pull a single frame out of video and save it as an image)

fmpeg -i nature.mp4 nature.gif (still image to a GIF)

ffmpeg -i nature.mp4 -t 2 nature.gif (to make it shorter)

ffmpeg -i nature.mp4 "fps=60" a.mp4 (Converts nature.mp4 into a.mp4 with a video frame rate of 60 frames per second (FPS))

ffmpeg -i nature.mp4 -t 2 nature.xyz (shows invalid argument)

commands for qrencode:-

qrencode -o hello.png "Hello World"

qrencode -o github.png "https://github.com/araj03380-star/lecture-13- (convert github URL into a QR code)

qrencode -x "test" (qrencode:invalid option --x)

4.WHAT BROKE, AND WHAT FIXED IT:
error 1:- command not found: ffmpeg,qrencode
      fix : installed it via homebrew using brew install ffmpeg  brew install qrencode

error 2 :- No such file or directory when running the command 
      fix : used cd to change into the correct folder containing the input files before running the command

5.THE FIVE STEPS:
1.open terminal
2.verify the input files
3.run the specific command
4.check the output file
5.commit and push


6.ONE THING YOU'D WANT TO TRY NEXT:
what specific tools did i use alongside ffmpeg

what errors did i actually run into

      
