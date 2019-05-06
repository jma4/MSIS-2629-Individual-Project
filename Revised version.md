## **Project Overview**  
  
The projct aims the goal of presenting relationships between Chicago's speed camera violation and traffic crashes to the Mayor of Chicago. Using Tableau software to explore supportive data, create visualizations and construct analyses base on findings. Through this case, I would like to present if speed cameras have impact on reducing speed relevant traffic crashes. 
  
  
## **Dataset Overview**  
  
[Speed camera violations dataset](https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4)   is about volume of violations that have occurred in Children's Safety Zones for each camera. Each violation has been collected by the camera and radar system and reviewed by two separate City contractors. Chicago experiences roughly 3,000 crashes annually between motor vehicles and pedestrians, about 800 of which involve children. The children's safety zone and automated speed enforcement program which uses enhanced signage and automated speed cameras to identify and ticket motorists who are breaking the law by exceeding the speed limits. (https://www.chicago.gov/city/en/depts/cdot/supp_info/children_s_safetyzoneporgramautomaticspeedenforcement.html) The registered owner of the speeding vehicle will be issued the speeding ticket. The [traffic crashes dataset] not only includes traffic crashed caused by speeding violations but also many other contributory causes. (https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if) In this case, I only focus on crashes that involved in exceeding authorized speed limit so I filtered out other contributory causes on creating visualizations. 
  
## **Dataset visualization and analysis**  
Visualizations used in this case which are created by Jui-Chuan Ma and uploaded in tableau public gallery that can be found [here.](https://public.tableau.com/profile/jui.chuan.ma#!/vizhome/Chicagospeedcameraviolation-crashesRevised/Dashboard) Facts and findings are presented follwed by corresponding graphics.
  
**Facts and Findings - Overtime**  
To start off, we see an interesting phenomena that a decreasing trend in the monthly speed camera violations but an upward trend in speeding relevant traffic crashes as figure 1 and 2 shows. It does not mean that speed cameras have negative influence on reducing traffic crashes. Combining these two variables together in figure 3, the amount of crashes shown as yello line has a low and steady line comparing to the amount of speed camera violations shown as blue line.   
  
![alt text](https://github.com/jma4/MSIS-2629-Individual-Project/blob/master/image/Monthly%20speed%20violations.png)  
  (Figure 1, [Monthly speed camera violations](https://public.tableau.com/profile/jui.chuan.ma#!/vizhome/Chicagospeedcameraviolation-crashesRevised/Dashboard))
  
    
![alt text](https://github.com/jma4/MSIS-2629-Individual-Project/blob/master/image/Monthly%20crashes%20revised.png)  
  (Figure 2, [Monthly speed relevant crashes](https://public.tableau.com/profile/jui.chuan.ma#!/vizhome/Chicagospeedcameraviolation-crashesRevised/Dashboard))  
  
![alt text](https://github.com/jma4/MSIS-2629-Individual-Project/blob/master/image/Monthly%20violations%20and%20crashes%20revised.png)  
(Figure 3, [Monthly speed camera violations and crashes](https://public.tableau.com/profile/jui.chuan.ma#!/vizhome/Chicagospeedcameraviolation-crashesRevised/Dashboard))  
  
  **Facts and Findings - Location**    
Then we move to figure 4 and 5, focusing on locations of the two datasets. Two streets, Western, Cicero and Kedzie Avenue, appear in both vsualizations. In figure 4, Western Avenue is considered by adding S Western and N Western together. Three of them show higher numbers in both graphics. Other than that, it seems that no other streets match in the top 10 violations and speeding crashes. Although it shows not very siginificant positive relations between street of violations and crashes. Higher number of violations still come with higher number of crashes.  

    
![alt text](https://github.com/jma4/MSIS-2629-Individual-Project/blob/master/image/Top%2010%20violations%20revised.png)  
  (Figure 4, [Top 10 violations by street](https://public.tableau.com/profile/jui.chuan.ma#!/vizhome/Chicagospeedcameraviolation-crashesRevised/Dashboard))
  
  
    
![alt text](https://github.com/jma4/MSIS-2629-Individual-Project/blob/master/image/Top%2010%20crashes%20revised.png)  
  (Figure 5, [Top 10 crashes by street](https://public.tableau.com/profile/jui.chuan.ma#!/vizhome/Chicagospeedcameraviolation-crashesRevised/Dashboard))  
  
  **Facts and Findings - Weekdays**    
People may think that most of speeding violations and crashes happen on Saturdays and Sundays. Suprisingly, the high peak of speed camera violations and speed relevant traffic crashes both locate on Fridays as Figure 5 and 6 shows. It may be one of the reasons that we only focus on traffic crashed caused by speeding. Most of crashes in weekends might be related to other causes. 
  
![alt text](https://github.com/jma4/MSIS-2629-Individual-Project/blob/master/image/Weekday%20violations%20revised.png)  
 (Figure 5, [Weekday violations](https://public.tableau.com/profile/jui.chuan.ma#!/vizhome/Chicagospeedcameraviolation-crashesRevised/Dashboard))  
    
  
  
![alt text](https://github.com/jma4/MSIS-2629-Individual-Project/blob/master/image/Weekday%20crashes%20revised.png)  
  (Figure 6, [Weekday crashes](https://public.tableau.com/profile/jui.chuan.ma#!/vizhome/Chicagospeedcameraviolation-crashesRevised/Dashboard))   
  
  
  
## **Revision History**  
  
### **Data**  
In the traffic crashes dataset of data exploration stage and first version, I filtered out speeding relevant crashes using two variables, (1)Exceeding authorized speed limit and (2) Exceeding safe speed to avoid crash. To compare with speed camera violations dataset, using crashes data that are caused by exceeding authorized speed limit is more reasonable. Other speeding relevant causes can not be catched by speed cameras. Then I use only one filter in the final version to show more accurate and related data to build visualizations and analyses.
  
### **Visualizations**  
![alt text](https://github.com/jma4/MSIS-2629-Individual-Project/blob/master/image/revision%20monthly%20violations%20and%20crashes.PNG)  
    
![alt text](https://github.com/jma4/MSIS-2629-Individual-Project/blob/master/image/revision%20top%2010%20violations%20and%20crashes.PNG)
    
![alt text](https://github.com/jma4/MSIS-2629-Individual-Project/blob/master/image/revision%20weeday%20violations%20and%20crashes.PNG)
