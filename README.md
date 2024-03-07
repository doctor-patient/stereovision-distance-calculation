This github pages gives the codes for a program I worked on during a coursewrk project in my college called IC201P Design Practicum. The aim of the project was to estimate the 
amount of water flowing in a river/stream, by recording a video of its flow from top of a bridge. The coding part had three components
    i. To get the velocity vectors of each pixel in the video.
    ii. To get the distance of the camera from the river.
    iii. To multiply the distance of each point of the river to the camera with the velocity, and get the actual surface velocity vector.
    iv. To extract the velocities along a line.
    v. To put it in a function for estimating the flow.
    vi. To send an email message, and compile the data in an excel. (As anyone can say, the parts i., ii. and v. are the most important ones)
My work as group leader was the parts ii., iii., iv., and vi., along with the final integration. Even though we ended up using only a single camera implementation for the 
project (which has a slightly different code than what is given in this repository, though the basic concept is the same, i.e., using the arc length and angle to estimate the 
radius), in this repository I have attached the code for how to calculate the distance between the flowing water and the camera stereovision. For better understanding, please 
feel free to refer to the presentation, report or the poster.
