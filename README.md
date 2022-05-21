                             Indian Institute Technology Roorkee,India
                                                                   
                   Artificial Intelligence and Electronics Society II year Project
                                                            
                                  Project Mentor :-Manav Saraf
                                                                             
                                         Team Member
                                                             
                         1) Ritesh Kumar Gupta (Electrical Engineering)
                         2) Mohit              (Mechanical Engineering)
                         3) Shubh Balodi        (Electronics and Communications Engineering)
                         4) Saurabh Singh      (Electrical Engineering)
                         
                                      
                                      Problem Statment
                                       
                  * Room automation of IIT Roorkee Hostel, automating fans and lights.
                  * Developing an end to end solution which can be controlled through mobile app .
                                                                             
                                     
                                     ** Solution approach **

                                          Level:-1
**Checking the functionality of the circuit designed using Blynk app**

* Made a basic bread board circuit and checked its functionality using switches.

* Used Blynk app to control the appliance using wireless means.

* Integrated the functionality of Blynk app with the tactile switches to control the appliance by manual switching and through Wi-Fi parallelly.

                                          Level:-2
**Creating live voltage equivalent of the designed circuit**

* Powered the circuit directly from the power supply.

* Replaced devices with 220V rated equipment like light bulbs and relay switches.

* Used Google Home App to connect the devices to be controlled.


                                          Level:-3
**Creating a website for user interaction**

* Designed a website using React framework with authentication to remove the necessity of google home.

* Fetching the data from Sinric Pro through API calls.

* Checking the online availability of the devices and changing its state while maintaining the functionality of the tactile switches.








                                     
                                                                             
                                **Steps to Automate the Room**
                                                                             
                                                                             
                                           
* Download the Zip file of the project to your local setup, and extract the full code directory from the zip file.
* The whole Room Automation directory consists of Arduino Code and website Code. 
* Open the Node Mcu code through your Arduino ide.
* Open the terminal.
* Go to the room automation directory.
* Install the node modules and other dependencies to the project through the command “npm install”.
* After the installation of all dependencies starts the local server by “npm start” command.
* Go to the Sinric pro website "https://sinric.pro/index.html".
* Complete the sign-up process through Email.
* Generate the app key and secret from there and add it to the Node MCU code as it will be required to establish the connection between the Node and Sinric pro website.
* Add the devices on the Sinric Pro website and add generated device id to the Node MCU code.
* Compile and upload the code to the Node MCU.
* Open the local server http://localhost:3000/.
* Login here with the Sinric pro credential. 
* In the dashboard tab, all the devices will be present. So you can able to control the state of the devices by clicking on the Turn on and Turn off button on the website.
                              
                                   **Thanks**
