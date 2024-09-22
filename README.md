# Pan-Tompkins-algorithm

### About
Pan and Tompkins (1985) “developed a real-time algorithm for the detection of QRS complexes in electrocardiographic signals, which is capable of detecting the QRS complex based on slope, amplitude and width.
![QRS](https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/ECGrita.svg/1920px-ECGrita.svg.png)

The QRS complex represents the rapid depolarization of the ventricles of the heart, which generates cardiac contraction. The main difficulty in automatic detection of the QRS complex lies in the fact that the ECG signal is often contaminated by background noise, motion artifacts and other elements, so it is crucial to highlight the QRS features while attenuating interference. A number of filters are available to help detect these depolarization points.

![QRS](https://upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Pan-Tompkins_algorithm_BlockDiagram.png/1100px-Pan-Tompkins_algorithm_BlockDiagram.png)

###  Libraries 
- Numpy
- Scipy
- wfdb
