# # How to Read Bitmap image and show on LCD
## Step1: Choose Tool
* Use imhex to show image in hex code: [Official Website](https://imhex.werwolv.net)
![BMP_img](../Images/BMP_imhex.png)

* Use Photo Pea to edit image and export as .bmp file: [Photopea](https://www.photopea.com)
![BMP_img](../Images/BMP_photopea.png)

## Step2: Decode BMP
* Refer to [BMP File Format Document](http://www.ece.ualberta.ca/~elliott/ee552/studentAppNotes/2003_w/misc/bmp_file_format/bmp_file_format.htm)
*  Split Header and Pixel Data
*  Because this image only have 3 kinds color, mark then 0x01: White, 0x00: Black, 0x03: Yellow

![BMP_img](../Images/BMP_Hex.png )

 * Confirm data and image related direction

![BMP_img](../Images/BMP_Direction.png )

## Step3: Show on LCD
* Turn into buffer in code

![BMP_img](../Images/BMP_Code.png )

* Done!

# [Go Back](../README.md)
