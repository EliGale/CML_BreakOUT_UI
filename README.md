# CML_BreakOUT_UI

This app provides a UI for the CML Breakout tool to enable easy SSH access to devices in a CML lab environment.

## Installation

To run the app, please follow these steps; otherwise, you will receive the message **"App is damaged and can't be opened."**

1. Download the application.  
2. Clear all extended attributes using the terminal with the following commands:

   **Note: In this example, the application is located in the Downloads folder.**

   ```
   cd ~/Downloads
   xattr -cr CML-BreakOUT-UI.app  
   ```

3. Open the app.

## How to Use It

1. Download the app.  
2. Currently, the app does not have an Apple Developer license. As a workaround, please ensure you "Clear all attributes" to avoid the message **"App is damaged and can't be opened."**

To clear the attributes, use these commands assuming the app is located in the Downloads folder:

```
cd ~/Downloads
xattr -cr CML-BreakOUT-UI.app
```

3. Fill all the information and click **"Save"**.
The save button will generate the config.yaml file and save all the information provided in this file.

4. Click **"Run"**
The Run button will execute the commands run and UI of the breakout tool. This initialize the HTTPS service that will provide the SSH access to the CML lab devices. 

5. Click **"Open"** will open the default  web page "http://[::1]:8080/#/". By default port 8080 is the default local port. **Do not confuse this with the port provided when filling the box information fields**.

6. In the web page opened for the service, **click at the top right refresh button"**.  

7. Final step, click on the enable button of the desire active lab, to enable the SSH access.




