# How to use Nano Series Duplex hotSPOT?  
Nano Serial Duplex hotSPOT UserGuide  
 
> Summary： Guide for Nano Series Duplex hotSPOT  
 
> Contact： bi7jta@gmail.com   
 
### How to use the Nano Series Duplex hotSPOT?  
#### 1st  Get ready for pi-star OS,Connect SMA ANT,Connect RPi to hotSPOT use GPIO.   
#### 2nd  Controller Mode:Duplex Repeater (also make sure to set duplex flag 1, not 0)  
http://pi-star/admin/configure.php  
http://pi-star/admin/expert/edit_mmdvmhost.php   

#### 3rd  set RX/TX Frequency, UHF and VHF is possible 
RXFrequency  434755000  
TXFrequency  439755000   
NOTE: set UHF TX - RX > 5MHZ to get better performance 
Only use amateur frequencies. Check your countries regulations to use the correct amateur radio frequencies!    

#### 4th set offset in section   
RXOffset=-300    
TXOffset=-300   
NOTE：If not set, BER may be quite high. -300 is the estimated offset for this batch of 14.7456MHz TCXOs.  
You can also adjust the value for smallest BER.  

#### 5th DMR, set static talkgroups for Timeslot 1 and Timeslot 2  (Fist Login)   
eg. https://brandmeister.network/?page=hotspot-edit&id=4600060     
NOTE: You can use your personal DMR-ID with appended SSID XX, like 4600060XX. XX from 01 to 99, for different hotSPOTs    

### All update status will be published    
https://groups.io/g/nano-mmdvm or join facebook userGroup     
https://www.facebook.com/groups/nano.mmdvm/    

![图片装载中](/images/user_guide_where_tx.png)     
[点击查看大图](https://github.com/nano-mmdvm/Duplex_hotSPOT/raw/master/images/user_guide_where_tx.png)    
 

Continue update ...     

Contract me: bi7jta@gmail.com    

