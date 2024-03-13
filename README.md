# Principal Component Analysis (PCA) on handwritten digits
-----
## GOAL: Figuring out which handwritten digits are most differentiated with PCA.

**Imagine you are working on an image recognition service for a postal service. It would be very useful to be able to read in the digits automatically, even if they are handwritten.**

**This project uses a dataset of handwritten digits (a very famous data set) and I will perform PCA to get better insight into which numbers are easily separable from the rest.**

# Data

    Background:

    E. Alpaydin, Fevzi. Alimoglu
    Department of Computer Engineering
    Bogazici University, 80815 Istanbul Turkey
    alpaydin '@' boun.edu.tr


#### Data Set Information from Original Authors:

We create a digit database by collecting 250 samples from 44 writers. The samples written by 30 writers are used for training, cross-validation, and writer-dependent testing, and the digits written by the other 14 are used for writer-independent testing. This database is also available in the UNIPEN format.

We use a WACOM PL-100V pressure-sensitive tablet with an integrated LCD and a cordless stylus. The input and display areas are located in the same place. Attached to the serial port of an Intel 486-based PC, it allows us to collect handwriting samples. The tablet sends $x$ and $y$ tablet coordinates and pressure level values of the pen at fixed time intervals (sampling rate) of 100 milliseconds.

These writers are asked to write 250 digits in random order inside boxes of 500 by 500 tablet pixel resolution. Subjects are monitored only during the first entry screens. Each screen contains five boxes with the digits to be written displayed above. Subjects are told to write only inside these boxes. If they make a mistake or are unhappy with their writing, they are instructed to clear the content of a box by using an on-screen button. The first ten digits are ignored because most writers are not familiar with this type of input device, but subjects are not aware of this.

[SOURCE](https://archive.ics.uci.edu/ml/datasets/Pen-Based+Recognition+of+Handwritten+Digits)
