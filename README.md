### While waiting for the official Tuya app to start working again in Homey, I decided to try Tuya Cloud and see if I could make AI integrate more devices, and it worked!

I’ve added almost every Tuya device Homey ignores, like temperature sensors, soil sensors, a universal remote and the movement detector from a camera, in just a few minutes!


You’ll need to:

•	Download **Cursor** or another AI coding app: [https://cursor.com]

•	Downloading the **Tuya Cloud github repository**: [https://github.com/jurgenheine/com.tuya.cloud] 

•	Install **Homey CLI**: [https://apps.developer.homey.app/the-basics/getting-started] 

•	Add your devices in the **Tuya mobile app**: [https://play.google.com/store/apps/details?id=com.tuya.smart&pli=1]

•	Create a **Tuya cloud project** using the credentials from the Tuya mobile app: [https://platform.tuya.com/cloud] 

•	Find your devices in the project’s **Devices**, select one and go to **Debug Device**.

•	Copy **Device information**, **Standard Instruction Set** and **Standard Status Set**, and ask Cursor to add a new device.

•	Open a **terminal window** in the folder of the downloaded repository, and run **homey app install** to upload it to Homey.

•	Open **Homey**, configure the **Tuya Cloud app** with api key and password from the project in the Tuya web app.

•	Add a **New device**, choose **Tuya Cloud**, choose the category of devices, and your device should appear.


AI made it so easy anyone could make it work. Some devices like Fingerbot shows as offline in the web app, so I am unable to operate it. Next I’ll try to make my camera capture an image and display it.


I’ve just started looking into this, but ideally new device ids and settings should be collected in a public list. Maybe someone knows the Tuya Cloud code well enough to modify it so we can just drop in a yaml file for each device?


 
**Tuya web app:**

 <img width="622" height="521" alt="image" src="https://github.com/user-attachments/assets/d80157ec-b0b9-46c9-8c9f-80db2160e6d8" />

**Device List:**

 <img width="380" height="208" alt="image" src="https://github.com/user-attachments/assets/6c5a833b-9da0-48b5-8966-6ab50919e7ce" />

**Device Information:**

 <img width="579" height="651" alt="image" src="https://github.com/user-attachments/assets/01daee20-6e95-4276-b328-51e0efae133e" />

**Standard Status Set:**

 <img width="875" height="678" alt="image" src="https://github.com/user-attachments/assets/674c94a4-3eb4-482a-a221-2f30747146fb" />

**API key:**

 <img width="689" height="599" alt="image" src="https://github.com/user-attachments/assets/bfa13c3e-1c3f-4592-9e0b-bcd389be8b4f" />

**Homey:**

 <img width="268" height="319" alt="image" src="https://github.com/user-attachments/assets/fcb63aea-14de-4fd1-bcc1-0e9ba608f400" />

**Tuya cloud app settings:**

 <img width="500" height="673" alt="image" src="https://github.com/user-attachments/assets/b12b1f11-ebb2-44ec-9993-8855d58484ab" />

**Add new Tuya cloud device:**

 <img width="446" height="543" alt="image" src="https://github.com/user-attachments/assets/ec8bfdc7-fc8c-4e61-b8d7-aa8438f3e435" />


