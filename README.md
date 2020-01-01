# Angular Webapp

## RUN THE FOLLOWING STEPS >>> AFTER ENSURING API GATEWAY is Succesfully Running  

1. BUILD: docker image build -t mooneshkachroo/webapp:0.0.1-RELEASE .
2. RUN: docker run --network locationtracker -p 80:80 --env SPRING_PROFILES_ACTIVE=localhost mooneshkachroo/webapp:0.0.1-RELEASE 

  

