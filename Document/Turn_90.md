# Turn LCD 90 Degree
## 1. Why need turn 90 Degree
* Default LCD Module is showing vertically
* If try to show in horizontally, text character still vertical
![LCD_img](../Images/LCD_Direct.png)
## 2. Build 90 degree text font
* Use [BitFontMaker2](https://www.pentacom.jp/pentacom/bitfontmaker2/)
![LCD_img](../Images/LCD_Bit.png)

* Set Height 10 pixel and width 8 pixel, character add 2 pixel margin space
* Turning into list and save into char_pixels dictionary
![LCD_img](../Images/LCD_Code.png)

* Add function in Vertical_LCD class, can select by char and setting x, y position and character color
![LCD_img](../Images/LCD_func.png)

## 3. Test and Result
* Et voila!
![LCD_img](../Images/LCD_res.jpg)

# [Go Back to Readme](../README.md)