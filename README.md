# How to use Nano Series Duplex hotSPOT?  
For Nano Serial Duplex hotSPOT UserGuide  
 
> summary： Guidance for Nano Series Duplex hotSPOT  
 
> Collate： bi7jta@gmail.com   
 
## 1st  Get ready for pi-star OS,Connect SMA ANT,Connect RPi to hotSPOT use GPIO.   
![Image loading...](/images/Duplex.jpg)     
[View large Image](https://github.com/nano-mmdvm/Duplex_hotSPOT/raw/master/images/Duplex.jpg) 

## 2nd  Controller Mode:Duplex Repeater (also make sure expert mode Duplex flag 1 not 0)  
http://pi-star/admin/configure.php  
http://pi-star/admin/expert/edit_mmdvmhost.php  
   

## 3rd  set RX/TX Frequency ,support UHF ,like 
RXFrequency  434755000  
TXFrequency  439755000   
NOTE: set UHF TX - RX > 5MHZ to Get better performance     
Just work at amateur frequencies, and different countries have different amateur frequencies.    

![Image loading...](/images/user_guide_config2.png)     
[View large Image](https://github.com/nano-mmdvm/Duplex_hotSPOT/raw/master/images/user_guide_config2.png)   


Program your DMR Radio Channel
![Image loading...](/images/Radio_Config_for_duplex.png)      
[View large Image](https://github.com/nano-mmdvm/Duplex_hotSPOT/raw/master/images/Radio_Config_for_duplex.png)   

## 4th set Offset in section   
RXOffset=-300    
TXOffset=-300   
NOTE：If not set,Error Rate % will hight, -300 is the offset of this bath 14.7456MHz TCXO offset.  
You can also abjust the parameters that make the Error Rate % to the lowest. 
 
![Image loading...](/images/user_guide_expert_config.png)     
[View large Image](https://github.com/nano-mmdvm/Duplex_hotSPOT/raw/master/images/user_guide_expert_config.png)  

## 5th DMR, Set Static Talkgroups for Timeslot 1 and Timeslot 2  
eg. https://brandmeister.network/?page=hotspot-edit&id=4600060     
NOTE:Can use 4600060XX XX is 01~99 ,for different hotSPOT    
![Image loading...](/images/Config_BM_Static_Group.png)     
[View large Image](https://github.com/nano-mmdvm/Duplex_hotSPOT/raw/master/images/Config_BM_Static_Group.png)   

## All update status will publish to email group    
https://groups.io/g/nano-mmdvm or join facebook userGroup     
https://www.facebook.com/groups/nano.mmdvm/      

![Image loading...](/images/user_guide_where_tx.png)     
[View large Image](https://github.com/nano-mmdvm/Duplex_hotSPOT/raw/master/images/user_guide_where_tx.png)     
 
![Image loading...](/images/user_guide_ui.png)     
[View large Image](https://github.com/nano-mmdvm/Duplex_hotSPOT/raw/master/images/user_guide_ui.png)   
 
### Demo live Duplex hotSPOT (Please do not modify anything,TKS!)  

http://bi7jta.myq-see.com:8088/  

## Config template for TYT-MD380 and Pi-Star_ver0327  
https://github.com/nano-mmdvm/Duplex_hotSPOT/raw/master/Duplex_Template_Config_27-Mar-2018.zip  
https://github.com/nano-mmdvm/Duplex_hotSPOT/raw/master/Config_TMP_Duplex_hotSPOT_TYT_MD380G_.rdt    
The program tools also in this page,with MD-2017,you can find it      
https://github.com/nano-mmdvm/Duplex_hotSPOT/raw/master/MD-380G.exe 

## Discuss and share
Youtube video https://goo.gl/xdH9vC   
Facebook Group https://goo.gl/Zz1mp5 

## How to upgrade firmware?  
See https://github.com/nano-mmdvm/MMDVM_HS_firmware/blob/master/how-to-upgrade-nano-duplex-fw.md 

## Need help
Join facebook group,view the status and publish your issue (I like this way,not all issue I can solve ).   
https://www.facebook.com/groups/nano.mmdvm/  

Continue update ...   
All the guide will move to my Google blog soon http://bi7jta.blogspot.hk/  



