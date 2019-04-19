[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JLbnAUmWTxrRtMDrZdPmQR2l7Mw9h3e5)

-   ResNet50 and Xception were too heavy for this assignment, i found that out by training them for several epochs and my training accuracy varying getting close to 90% and  validation still hanging at 20% this happened within 15 epochs for Xception.

-   Tried to extract the images from the given bounding box data and then resized them, instead of getting a higher accuracy i succumbed to worse results and inferred that maybe background here was substantial information. Wasted a lot of days in figuring out why this did not work.

-   Added custom image augmentation for creating random black blobs in images but did not give substantial increase in accuracy results were pretty much the same.

-   Best validation accuracy achieved was 51% and cyclic LR (custom function again) was used.

### TODO

- [x] Cyclic LR
- [x] Try multiple Architectures.
- [x] Custom Augmentation
- [ ] Try Focal Loss
- [ ] Make a custom architecture.
