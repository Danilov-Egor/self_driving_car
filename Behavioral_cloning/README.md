<H3>Behavioral cloning project</H3>

<H5>Overview</H5>  
The idea of this project is to clone human's behavior on the road. First we have to ride several laps and to collect data: images that are made with camera mounted on a bonnet and steering angle. Than the CNN will have to predict the steering angle of the car at that moment.  

CNN architecture:  
<img src="architecture.PNG" alt="drawing" width="400"></img>  

However, driving normally is not enough as NN will not know how to return back to the center of the road. To teach a model do that we have to turn right and left and then return back to the center of the road. Also, our data is very unbalanced, because the car mostly drives straight ahead. So, we can use downsampling to balance our observations.  

Watch video:  
[![Watch the video](track_1_intro_s.PNG)](https://youtu.be/hf6iXHCsHmM)
