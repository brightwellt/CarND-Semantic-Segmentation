# Notes on CarND-Semantic-Segmentation
# Thomas Brightwell, December 2017

## Overview
Code based upon Chapters 9, 10 and 11 in course, along with project walkthrough video.

Network structure derived lessons and from 
https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf

Network was run on AWS Spot Instance, Ohio.
Controlled via Putty from the Uk. Settled on 50 Epochs, batch size of 5, which took about an hour to run.

Trained network appears generally successful, though some frames with deep shadow are not identified successfully.

## Going forward
My next step - probably in the new year - is to try this on videos I have of water - I work in the Marine Industry, 
and it'll be interesting to see if water vs. land / vessels can be readily identified. 
