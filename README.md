# Twilio_Auto_Dialer
This autodialer was created in Summer of 2024 by graduate data science interns Jash Dharia Jaliwala and Shuham Gaikwad with guidance from Shafeeq and myself (Jason). It was the basis for the dialing capabilities of an AI-driven marketing app.

# Project Background and Purpose
Twilio Flex is Twilio's in-house autodialer, but it is not free and has limited integration capabilities. This custom-coded autodialer allows teams to bypass the need for Flex or other paid, closed-source alternatives.

# State of the Code
The code worked for us. Given Twilio's giant marketshare and otherwise easy-to-use UI, you'll find that using Task Router(s), queues, and the other advanced callcenter backend features can be rather tricky. What this code does is to help you save at least a few hours of headaches if you're trying to make a dialer with that backend. 

We had numerous versions of the project. The code presented here is some compromise between being (a) the most up-to-date and nearly production ready and (b) what's readily available and convenient to me, given that Jash managed the codebase, the internship has ended, and, sadly, our small and heretofore fast-growing startup recently fell victim to sabatoge by a disgruntled executive and dissolved. The version of the project in this main branch did not have a pretty UI. 

There's another version or two with a prettier UI. If I come across it, I'll add it in another branch, but I think there was a bug in its call routing under certain conditions, which is (hopefully) resolved in this copy.

# Deployment
We tested the following methods of deployment:
  - cPanel
  - Localhost 
  - Heroku

Due to the use of PHP, cPanel seems to be an especially advantageous approach. However for earlier iterations that more closely resembled our upstream example's repo, Heroku was very convenient.

# Maintenance
This project is most definitely *not* under active development or being maintained. Feel free to fork it and make your own project under any name if you're interested in maintaining it.

# Our Inspiration
We began with a combination of documentation and a forked copy of this repo, which is authored by a Twilio employee:
https://github.com/tigerfarm/tigtaskrouterworker

While exceedingly helpful and educational, we found severe deficiencies in that repo (no offense to the author). I will leave it to the former interns to detail those shortcomings. I believe I can say that by the end of the project, little or no code from the upstream repo remained, but after so many iterations I will again have to leave that detail to Jash and Shubham to confirm. At the very least, the 'tigerfarm' repo contains very nice infographics and videos that we aren't including here, so check it out.

# Citing this Repo
If you find this repo useful, give a credit to Jash Dharia Jaliwala and Shuham Gaikwad.
