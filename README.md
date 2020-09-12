# ObjectDetectionUsingYOLO
## Experience of object detection research when I was intern at NASA.

### Challenge

Environment factor affects the accuracy of prediction
- Light condition
- Environmental blur
- Motion blur

### Solusion

##### Algorithm

Improving the algorithm for specific images could give us a better result.

Using Contrast Enhancement to enhance low light images, Some test cases attached below.

#### Test Case 1
![Picture5](https://user-images.githubusercontent.com/44939469/92987871-560bf380-f47b-11ea-8f76-1f01e01b8048.jpg)
![Picture6](https://user-images.githubusercontent.com/44939469/92987872-57d5b700-f47b-11ea-966e-0df39de7f1cb.jpg)

#### Test Case 2
![Picture7](https://user-images.githubusercontent.com/44939469/92987873-57d5b700-f47b-11ea-82f4-6ca77d8f9865.jpg)
![Picture8](https://user-images.githubusercontent.com/44939469/92987874-586e4d80-f47b-11ea-9f39-90976aaf149a.jpg)

##### Data Collection

YOLO has advantage of generalizable representations, so I thought I can use images from video games to create the dataset.

I first tried to detect object from some video games, here are some examples.
![Picture1](https://user-images.githubusercontent.com/44939469/92987442-34a90880-f477-11ea-9429-53c99c572a31.png)
![Picture2](https://user-images.githubusercontent.com/44939469/92987443-3672cc00-f477-11ea-972a-e9b1f59ac1c2.png)
It is obvious that accuracy of object detection is higher in modern video games with powerful GPU.

After some tests, I recorded video from *Red Dead Redemption 2*. And used it to make dataset for my research at NASA.

![Picture3](https://user-images.githubusercontent.com/44939469/92987444-37a3f900-f477-11ea-8e3b-9b718d3efbc7.jpg)
![Picture4](https://user-images.githubusercontent.com/44939469/92987445-38d52600-f477-11ea-8930-79dd7b537fa7.jpg)

###### Some thoughts

It is possible to apply object detection in future AI when it needs to interact with video games based on visual input.
