# Hospital_Project
Sathepan Nagendrarajah (100454393) 
Tracking Dotted Pathways for Hospital Emergencies

Abstract:
  In a society where we accept technological revolution and enhance performance of services in various industries, it is clear that medical industry, especially the hospitals have a lot of improvements that can be made. The way hospital systems organize the incoming patients can be handled more appropriately with technological advancements. Starting from the time patients are admitted into the ambulance, and from the time the patients are transported to the emergency wards, the average waiting time patients wait for treatment or operation, it can be seen that a lot of this time can be better scheduled to provide these medical services faster to patients.  

  One innovation that can reduce the time inefficiency is deploying smart wheelchairs. Smart wheelchairs will be able to do basic checkups, check the medical condition of patients and assign the patients to a facility within the hospital. Presently, patients are able to identify which facility to go based on a pathway of colour coded circles. One system which is required for this to work is a computer vision processing unit. The final product of this product will be able to support the autonomous transport of patients through the different pathways that exist in the hospitals. The first deliverable for this type of system would be a working computer vision software program that is able to track the pathway of colour coded circles. 

  In this project, mp4 video recordings of an actual hospital pathway of colour coded circles are used, and the software program should be able to detect pathway of circles of different colour. One of the project requirements is that it should be able to detect the circles of specific colour based on the video recording of the hospital pathway. The second project requirement is that it should be able to detect occluded circles, or circle-like polygons that are not completely round. The second requirement will be useful when worn out, or obstacle(s) partly blocking the circles can still be identified as circles. 

  In this project, two methods were programmed in order to achieve the project requirements. One method was to detect coloured circles of interest using contour points and calculating moments from the calculated contour area to find the centroid or center of the detected circle(s). Another method was using a series of filtering in order to detect circles of interest using Hough Transform. Both methods used ROI or masks to select the colours of interest. Also, both methods showcase the trajectory of the path that should be taken by appending center points into a list, iterating through the list, and drawing red lines from the previous detected circle center to the current detected circle center.

