# CSC-4890----Computer-Vision

Part A: 
  Using images of the Charuco board we deduced the camera calibration matrix as
  such:
  
  
  
  [[412.40450061   0.         237.63729882]
  
  [  0.         427.44913266 296.06487431]
  
  [  0.           0.           1.        ]]
 
 Part B:
 Using an image we deduced the real world dimensions of a 
 specific point on the board
 
 
 length along x axis is :  -20.08613012439237
 
 length along y axis is : -11.04462865793694
 
 length along z axis is : -44.21633556738175

Part C:
  
  Question 3:
    Yes it is feasible and was able to set up an RGB stream and a depth map stream 
    using the mono and stereo cameras and dedduced that the maximum FPS was at 
    60 and the resolution was at 1080P.
  
  Question 4:
    Deduced the actual camera calibration matrix using the provided calibrate.py
    script to find that the matrix was:
    
		
    [[457.1668   0.         320.9126  ]
    [  0.        456.0823   240.56018 ]
    [  0.           0.           1.   ]]
   
	 
	 Therefore by comparing this matrix from the matrix obtained in part A we can
    deduce that the matrix's are quite similar and are off potentially due to the
    images being taken and used for each of the respective codes. 
