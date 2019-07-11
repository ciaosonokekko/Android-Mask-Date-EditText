# Android Mask Date EditText


# What is it? 
This library simplified the way of get date from user input, Allows the user to enter a date as a text and then verify it based on date format, divider character and min or max date with other options.

------ 

# How to use it? 

## First Install

```gradle

implementation 'com.github.salahamassi:android-mask-date-editText:v1.01'

```
------ 

## Second Usage
1- Define new DateEdit text inside you layout xml
```xml
 <com.msa.dateedittext.DateEditText
               android:id="@+id/dateEditText"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"/>
```
2- start listening to user input from your acticity, fragment or any android UI components
```kotlin
dateEditText.listen()
```
and just that's it!

------ 

## More options
please download the sample and watch the video to dive more deep.

### `DateEditText` attrs
* `dateFormat`
 	* You can choose between two format "ddMMyyyy" or "MMyy" maybe in the future i will add more, you can add and then make pull request. 
        
* `dividerCharacter`
 	* You can choose between two divider Character "/" or "-".
        
* `maxDate`
 	* set the max date which can user enter it as a string from xml and as a Date object from the code.

* `minDate`
 	* set the min date which can user enter it as a string from xml and as a Date object from the code.

* `autoCorrect`
 	* if you want to show error alert to user if he enters something invalid set autoCorrect = false, if you want autocorrecting to what the user inputing set it to "true".
        
        
* `helperTextEnabled`
 	* show helper text, Used just with TextInputLayout.

* `helperTextHighlightedColor`
 	* Highlighted helper text color for what user inputed.

# Screenshot
![Screenshot_1562879351](https://user-images.githubusercontent.com/17902030/61085592-5228af80-a439-11e9-9e83-a8eeb003b434.png)

# Video
(https://cloud.githubusercontent.com/assets/17902030/26277811/7dedf3f0-3d98-11e7-900e-4d0742c10b5a.png)](https://youtu.be/7X8RxxemEaQ)
# Developer contact 
   * [Facebook](https://www.facebook.com/profile.php?id=100006656534009)
   * [Twitter](https://twitter.com/salahamassi)
