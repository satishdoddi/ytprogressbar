# ytprogressbar

put this is in Build.gradle

implementation 'com.github.satishdoddi:ytprogressbar:1.0'

ytprogress ytp = new ytprogress(getApplicationContext(), progressbar1);

ytp.showProgress();
ytp.startTransition(500,500);
ytp.hideProgress(10000);
