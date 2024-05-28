# Handwriting Classification Challange

This is a small time-series challenge I did during my master's. All credit for the challange idea goes to **Dr. Sharon Ong**, Department of Cognitive Science and Artificial Inteligence, Tilburg University.

**Update:** My implementation of Rocket managed to win 2nd place in the competition :)

The objective of this challange is  to classify whether a child's handwriting is affected by dysgraphia. The data comes from the study by *Drotár and Dobeš, 2020* and is avaliable [here][https://github.com/peet292929/Dysgraphia-detection-through-machine-learning]. It was collected using a using a WACOM Intuos Pro Large tablet.
The features are numeric and represent the below over time:

* pen movement in the x-direction,
* pen movement in the y-direction
* whether the pen was on the surface (1) or in the air (0)
* the pressure of the pen on the tablet surface
* the azimuth of the pen on the tablet surface

**References**
Drotár, P., Dobeš, M. Dysgraphia detection through machine learning. Sci Rep 10, 21541 (2020). https://doi.org/10.1038/s41598-020-78611-9