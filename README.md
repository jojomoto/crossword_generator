# crossword_generator
This function ingests an image of a crossword puzzle grid and converts it into a matrix of black and white squares.

This is part of a larger project to eventually solve any crossword that has its picture taken and put into the program.

Currently the pictures need to be cropped before loading into the program. Eventually I will use some sort of simple ML or recogniztion technique to know where the grid is in the picture.

The crossword3.jpg picture is very blurry (This was on purpose to test the accuracy of the script). The bottom left corn square is incorrect for this image (assuming it is from bad cropping of the image). NOTE: If you ever noticed that the location of the black and white squares on a crossword grid always matchs up the same with the grid rotated 180 degrees. I will utilze this fact to increase accuracy in the future.
