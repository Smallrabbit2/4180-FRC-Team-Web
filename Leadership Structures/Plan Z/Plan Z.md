```mermaid
graph TB
robot["Robot Manager"]
Captain --> Leads
Captain --> Mentors
Mentors <--> Leads
Leads --> Comms
Leads --> Outreach
Leads --> Business
Business --> Finance
Business --> Marketing
robot --> Controls
robot --> Strategy
robot --> Engineering
perlim["Perliminary / Prototyping"]
crit["Critical / CAD"]
Engineering --> perlim
Engineering --> crit
Engineering --> Manufacturing
Controls --> Development
Controls --> Programming
Controls --> Electronics
Strategy --> Match
Strategy --> Scouting
Strategy --> Drive
Strategy --> Design
Design <--> perlim
```


![[Pasted image 20250411234710.png]]
