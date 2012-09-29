# Home Control 
_Control stuff in your house via twitter_
This project is created to have Arduino communicate about things via Twitter.  
Right now it's possible for Arduino to know when it's getting dark in a space, and to notify me by sending me an @ mention. When I reply with a string that contains "Lights on", a LED turns on. When I send my Arduino a message that contains "Lights off, the LED goes off".

I'm looking to expand this project with real lights and a remote. Also I might add more functions later (like temperature for example.)

## Libraries used
I used some libraries to come up with the result. Your dependancies are:

* [pyserial](http://pyserial.sourceforge.net) for reading/write your Arduino's Serial data
* [python-twitter](http://code.google.com/p/python-twitter/) a wrapper for communication between Twitter and Python

## Instructions
You should replace these lines of code with your own Twitter app API data:  
`api = twitter.Api(consumer_key='iQtIi2Ws9thbYzdVpXR9A', consumer_secret='Ah57xPprjvLWXx5Zd73F1caXD0J6G096n20dUSXo', access_token_key='842181841-htj7gl9DaWB08pJYARxDtTEdSFdqDrTEGnUydXAZ', access_token_secret='lm2eAlZwksCP3JbcmkDggFDP1LQkEMa8gACtJHSRDc4')`
You can apply for a Twitter API key here: [https://dev.twitter.com/apps/new](https://dev.twitter.com/apps/new).