# Internet_Eng-HW1
internet engineering hw1_2

## Resolving noisy image with  [median-filter](https://en.wikipedia.org/wiki/Median_filter/)
## Use the package manager [pip](https://pip.pypa.io/en/stable/) to install opencv-python.

```bash
pip install opencv-python
```

## How does the algorithm work!!!
The median filter is a non-linear digital filtering technique, often used to remove noise from an image or signal. Such noise reduction is a typical pre-processing step to improve the results of later processing (for example, edge detection on an image).
It uses neighbour pixles of its sides and choose the median of each selected matrix.So if there's any noise exists (corrupt pixles) , with this filter it changes the corrupted pixle , so  after doing this to all image matrix , hopefully there will be better image comparing the input image!



