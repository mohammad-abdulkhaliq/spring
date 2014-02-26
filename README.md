spring
======

Quick Guide

Download Gradle

add this line to .bashrc
export PATH=$PATH:path to your gradle folder/bin

Download Tomcat 7 

unzip folder then cd to bin folder
chmod +x * 

cd to conf
nano tomcat-user.xml
follow instructions on how to add a user then add one with role manager-gui
cd back to bin
./startup.sh

go to localhost:8080 

Run this

gradle wrapper (only once)


to immediatly run 

./gradlew bootRun

to create a war 

./gradlew clean build

you will find the war in build/libs in root of application to deploy just got to localhost:8080/manager/html/ and click deploy in bottom of the page.
