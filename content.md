
<!---
Version: 1.0 
-->
# Load a capture file in Wireshark
## INTRODUCTION MESSAGE
In this exercise, you will gain some basic experience using Wireshark to analyze network traffic. You will launch Wireshark and load a capture file for analysis. After loading the capture file, you will look for specific and detailed information contained in the network traffic capture file. After you complete this lab exercise, you will answer some review questions regarding the contents of the network traffic.
## COMPLETION MESSAGE

### Log on to WIN10
Log on to WIN10 using **Student** as the username and **Passw0rd!** as the password.

#### :warning: ALERT
Please ensure you click Done as you complete each task in this exercise. When you click Done for the final time, you will be presented with some review questions.




#### :computer: ACTIONS
>LODSProperties
>* VM = Lab 03 - WIN10



### Open capture file in Wireshark
On the desktop, double-click **rhino.cap**. Wireshark opens and displays the contents of the capture file.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/765474.png





### Determine MAC address
In Wireshark, select packet \#3. In the middle pane, examine the Ethernet II section. Note the MAC addresses of the two hosts are displayed. Please see the attached screenshot for confirmation of the identity of the MAC addresses.

#### :bulb: KNOWLEDGE
**NOTE**: The type of device is also displayed in the Ethernet frame.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/765483.png





### Navigate to specific packet
On the Wireshark tool bar, click **Go** and then click **Go to Packet**. In the Packet field, type **658**, and then click **Go to packet**.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/765482.png





### Find instances of a specific protocol
In the Expression file, type **imap**, and click the right arrow.

#### :warning: ALERT
Wireshark is case sensitive. Please ensure you use lower case letters for the protocol name.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/765484.png





### Search for text string in data
In the Expresssions field, type **ftp contains ASCII**, and press **ENTER**. Two packets that contain the string ASCII are displayed.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/765485.png





### Find packets that use a specific IP address
In the Expressions field, type **ip.addr ==207.68.173.245**, and press **ENTER**.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/765488.png





### Clear filter
In the Expression field, click the **X** to clear the filter.





### Begin review assessment
Click **Done** to close the lab instructions and answer a number of multple choice questions about the communications that take place in the capture.






