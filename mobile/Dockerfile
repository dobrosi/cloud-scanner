FROM bitriseio/docker-android:latest

WORKDIR /work

RUN cordova create hello && cd hello
RUN cordova platform add android
RUN cordova plugin add cordova-plugin-barcodescanner
RUN cordova build