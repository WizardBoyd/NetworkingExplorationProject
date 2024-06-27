# NetworkingProject
This was a project I developed during off times after my 2nd year at university along side my placement year, I followed a lot of concepts from Multiplayer Game Programming: Architecting Networked Games (Game Design)
by Josh Glazer and Sanjay Madhav.

although some stuff was a little outdated so I retargets the build to 2019 as I tried getting the build to work with MSbuild tools 2022 however I just could't as well as I was busy during these times.

# Running the server
if you build the solution in either debug or release (note please build using x32 as some warnings and errors occur with X64).

after building if you either use the windows CLI or any powershell you can launch the Server app with an argument for the server port

example: RoboCatServer.exe -45000

this would launch the server on the port 45000

# Running the Client

if you build the solution in either debug or release (note please build using x32 as some warnings and errors occur with X64).

after building you can run the exe through the CLI or powershell with these arguments Address (includes the port) and username

example: RoboCatClient.exe 127.0.0.1:45000 TestUser

this will launch you into the game connected to the server

you can launch multiple instances of the client to see the Networking in action
