# ytprogressbar

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

gradle

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.satishdoddi:ytprogressbar:1.0'
	}


And code is 

ytprogress ytp = new ytprogress(getApplicationContext(), progressbar1);

ytp.showProgress();
ytp.startTransition(500,500);
ytp.hideProgress(10000);
