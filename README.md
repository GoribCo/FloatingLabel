FloatingLabel
=============

FloatingLabel Allows you to create a blow kind of EditText.

To explain the concept well I have taken below image from http://dribbble.com/shots/1254439--GIF-Float-Label-Form-Interaction

![Animation Example](/form-animation-_gif_-1.gif)


Floating Lable project is in initial mode, where a few customization is provided like changing Text color of EditText and Its Lable


```java
<com.hardik.floatinglabel.FloatingLabelView
        android:id="@+id/label1"
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        floatview:floatHintText="Whatever hint you want to display"
        floatview:textColor="@color/blue"
        floatview:textTypeface="some_custome_font.ttf"/>
```
## Features 
* [Float Hint Text](#float-hint-text)
* [Float Hint Text Color](#float-hint-text-color)
* [Float Hint Text Style](#float-hint-text-style)
* [Float Hint Text Gravity](#float-hint-text-gravity)
* [Float Hint Text Size](#float-hint-text-size)
* [Float Hint Text Custom Typeface](#float-hint-text-custom-typeface)
* [Float Hint Text Background](#float-hint-text-background)
* [Actual Text](#actual-text)
* [Actual Text Color](#actual-text-color)
* [Actual Text Style](#actual-text-style)
* [Actual Text Gravity](#actual-text-gravity)
* [Actual Text Size](#actual-text-size)
* [Actual Text Custom Typeface](#actual-text-custom-typeface)
* [Actual Text Background](#actual-text-background)
* [Actual Text As Password](#actual-text-as-password)


### Float Hint Text
* Specifies the text for float hint label
```Android
	floatview:floatHintText="@string/app_name"
```
### Float Hint Text Color
* Specifies text color for float hint label both for focused mode and unfocused mode
```Android
	floatview:floatHintTextColorFocused="@color/blue"
        floatview:floatHintTextColorUnFocused="@color/green"
```
### Float Hint Text Style
* Specifies the text style, bold,normal,italic
```Android
	floatview:floatHintTextStyle="bold"
```
### Float Hint Text Gravity
* Specifies gravity of text left,right,top,bottom
```Android
	floatview:floatHintTextGravity="right"
```
### Float Hint Text Size
* Specifies text size
```Android
	floatview:floatHintTextSize="20"
```
### Float Hint Text Custom Typeface
* Specifies custom font. (It has to be in to the assets folder e.g. /assets/some_font.ttf)
```Android
	floatview:floatHintTextTypeface="Ithornet.ttf"
```
### Float Hint Text Background
* Specifies custom background. You can specify both color and drawable.
```Android
	floatview:floatHintTextBackground="@drawable/label_bg"
```
### Actual Text
* Specifies the text for editable text box
```Android
	floatview:text="Label 1"
```
### Actual Text Color
* Specifies text color for editable text box
```Android
	floatview:textColor="@color/red"
```
### Actual Text Style
* Specifies the text style, bold,normal,italic
```Android
	floatview:textStyle="bold"
```
### Actual Text Gravity
* Specifies gravity of text left,right,top,bottom
```Android
	floatview:textGravity="right"
```
### Actual Text Size
* Specifies text size
```Android
	floatview:textSize="20"
```
### Actual Text Custom Typeface
* Specifies custom font. (It has to be in to the assets folder e.g. /assets/some_font.ttf)
```Android
	floatview:textTypeface="Ithornet.ttf"
```
### Actual Text Background
```Android
	floatview:textBackground="@drawable/edt_bg"
```
### Actual Text As Password
```Android
	floatview:isPassword="true"
```



