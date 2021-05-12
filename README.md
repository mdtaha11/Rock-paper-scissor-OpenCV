# Rock-paper-scissor-OpenCV

The project is based on OpenCV implementation of rock, paper and scissors game where user can play the game with computer.
The projects is the derivation of counting number of fingers using OpenCV.
If number of fingers= 2, it detects Scissors
  number of fingers= 0, it detects Rock
  number of fingers = 5, it detects Paper
  
 The projects works on real-time, where it extracts frames from the webcam. The user places his hand in the drawn rectangle.
 The image is blurred using GaussianBlur, and converted to HSV image. Further dilation, erosion etc are carried out. 
 Threshold is defined to detect color of hand, and a mask is created using threshold. Then contours are drawn and convexityDefects is used to count number of fingers showm.
 Computer randomly displays his move anyone from rock, paper or scissors. The result is shown accordingly and is shown below.
 Computer only generates its move when the user changes his/her move and not with every frame.
 Result 1:-
 ![alt text](https://github.com/mdtaha11/Rock-paper-scissor-OpenCV/blob/main/rock.png?raw=true)
 
 Result 2:-
 ![alt text](https://github.com/mdtaha11/Rock-paper-scissor-OpenCV/blob/main/Paper.png?raw=true)
 
 Result3 :-
 ![alt text](https://github.com/mdtaha11/Rock-paper-scissor-OpenCV/blob/main/Scissors.png?raw=true)
