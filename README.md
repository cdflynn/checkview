# Check View
An animating check mark

![Sample App](https://github.com/cdflynn/checkview/blob/master/sample/img/check_sample.gif?raw=true)


## Usage
Add a `CheckView` to your layout

```xml
    <cdflynn.android.library.checkview.CheckView
        android:id="@+id/check"
        android:layout_width="200dp"
        android:layout_height="200dp"
        app:checkView_strokeColor="@color/green"
        app:checkView_strokeWidth="@dimen/check_stroke_width"/>
```

Note that you can specify a stroke width and color with xml attributes `checkView_strokeWidth` and `checkView_strokeColor` respectively.

Call `check()`:

```java
    mCheckView.check();
```


## Install

Add jitpack to your root `build.gradle`

```gradle
    allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

Add as a dependency
```gradle
	dependencies {
	        compile 'com.github.cdflynn:checkview:v1.1'
	}
```
