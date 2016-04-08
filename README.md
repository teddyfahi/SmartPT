
### Assignment Master of Applied Computer Science ###

Student Project, Module: MA220 - Architecting the Internet of Things, Westerdals ACT, Oslo.
This assignment take the form of an application-led project. 
Creator is: Teddy Falsen Hiis (teddyfahi@gmail.com).


### About SmartPT ###

SmartPT is a PT (personal training) system, based on NFC wearable sensors mounted on garment like gym t-shirts and smart training units. Instead of sowing in wearable technology to every possible body part in motion, SmartPT is a sensory system of which is applied to the object in training — such as a training mat, a barbell or a rod.

The delivered code is a proof-of-concept Android version of the application. 


### When looking into the code ###

All code is delivered as a .zip file through It'slearning. The code can be run through any web-browser simply by visiting the page http://teddyfh.com/iot/ using Android powered device which holds a NFC scanner.  See below for more information.

For prototyping purposes, the application is fixed to push-ups (training biceps) of 12 repetitions in a workout set. If desired, this can be changed in the attached file called 'push.html'



### How to test the solution ###

SmartPT is delivered as a web-application, based on the Bootstrap HTML5 framework. 
A NFC tag of write-rights is needed to test the solution. The NTAG21x Series is a functional solution to use.

- You need to write a simple URL record the NFC tag. The URL record is just one of many default NFC data set used to launch applications. Do this through the use of any NFC writer application. Find options in Google Playstore: https://play.google.com/store/search?q=nfc%20tags&c=apps&hl=en
- See information on how to write a NFC tag here: http://www.howtogeek.com/212117/how-to-use-programmable-nfc-tags-with-your-android-phone/
- Write the tag with the following URL record:
http://teddyfh.com/iot/push.html

Test the SmartPT prototype by:
-> using an Android powered mobile-phone and Google Chrome, open the following webpage: http://teddyfh.com/iot/ 
-> choose 'Biceps' (only option available for prototype)
-> tap NFC tag to collect approved workout repetitions by PT. Illustrated with sound.
-> when approved repetitions hit 12 the application goes into break mode of 30 seconds, counting down. Illustrated with sound.
-> tap 'Start Next Set' to continue workout


## Copyright and License

Copyright 2013-2015 Iron Summit Media Strategies, LLC. Code released under the [Apache 2.0](https://github.com/IronSummitMedia/startbootstrap-creative/blob/gh-pages/LICENSE) license.