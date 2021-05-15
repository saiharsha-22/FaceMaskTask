# FaceMaskTask
## Description
- We are given a dataset, in that data set for every image consists set of two images respectively. One is mask_image, and the other is rgb_image. Our task is to get the ouput of the image by masking the rgb and mask image respectively. 
- Libraries:
    - numpy
    - cv2
    - matplotlib

## Setup instructions

- First download the dataset using the given drive link and unzip the files using the command given below.
```
!unzip filepathname
```
- First we need to fetch the image from the file location
- After fetching the images, we need to do some data preprocessiong of the given dataset. The code is written inside the "".ipynb" file. 
     - Resizing of the image can be done
     - check the image by ploting it 
![Screenshot (859)](https://user-images.githubusercontent.com/61947484/118351868-f91d8b80-b57b-11eb-9784-cae64176273a.png)

- Now we can start using the different bitwise operator to merge these two images properly. 
Since Bitwise and was working sucessfully, so I have use that command to implement.
```
cv2.bitwise_and(img_path, img_path, mask = mask)
```

## Output
- After performing the above operation you will get the output as shown below: 

![Screenshot (860)](https://user-images.githubusercontent.com/61947484/118351982-95e02900-b57c-11eb-9581-0940b1dd3e36.png)

- For refernce I have attached my pyhton file you can refer that. 