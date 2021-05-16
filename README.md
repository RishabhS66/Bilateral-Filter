# Bilateral Filter
```
Coded By: Rishabh Srivastava
```
A bilateral filter is a non-linear, edge-preserving, and noise-reducing smoothing filter for images. It replaces the intensity of each pixel with a weighted average of intensity values from nearby pixels. The basic idea underlying bilateral filtering is to do in the range of an image what traditional filters do in its domain. Two pixels can be _close_ to one another, that is, occupy nearby spatial location, or they can be _similar_ to one another, that is, have nearby values, possibly in a perceptually meaningful fashion.

The bilateral filter can be formulated as :
<div align = "center">
  <img src = "https://user-images.githubusercontent.com/39689610/118398869-09b32c00-b678-11eb-877e-8084c53d357a.png" width = "450" height = "200">
</div>
<br>

As the range parameter σr increases, the bilateral filter gradually approaches Gaussian convolution more closely because the range Gaussian widens and flattens, which means that it becomes nearly constant over the intensity interval of the image. Thus, as σr increases, the image gets more blurred.

As the spatial parameter <img src = "https://user-images.githubusercontent.com/39689610/118399970-564d3600-b67d-11eb-9105-079181af4a14.png" width = "300" height = "409"> increases, the larger features get smoothened.


This repository includes code that applies a bilateral filter on the image _MinaretLake.jpg_.

The **results** are displayed below:

<div align = "center">
  <kbd>
    <img src = "https://user-images.githubusercontent.com/39689610/118399970-564d3600-b67d-11eb-9105-079181af4a14.png" width = "300" height = "409">
    <img src = "https://user-images.githubusercontent.com/39689610/118399979-5ea57100-b67d-11eb-9d24-38c1b91e9e31.png" width = "300" height = "409">
  </kbd>
</div>
