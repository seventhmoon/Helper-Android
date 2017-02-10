# Helper-Android
Helper Functions for Android

[![Build Status](https://travis-ci.org/seventhmoon/Helper-Android.svg?branch=master)](https://travis-ci.org/seventhmoon/Helper-Android)

## Add the JitPack repository to your build file
### Add it in your root build.gradle at the end of repositories:
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

## Add the dependency by adding this into modules' build.gradle
	dependencies {
	        compile 'com.github.seventhmoon:Helper-Android:v1.0'
	}
