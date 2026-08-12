# Ender-7-Raspberry-Pi-MainsailOS Conversion
I am creating a tutorial to control an Ender7 3D printer with a pi using mainsailOS, I will try to make this so that anyone even you have never played with linux before can follow it

I am using parts I already had leftover and did not buy new parts I am starting with:
- Ender 7
- Pi 3
- Pi 3 Charger
- small non-touchscreen so see what the pi is doing
- 32 gig Micro SD card
- USB to USB type C cable (pi to ender 7)

## Part 1 — Installing Mainsail OS
- Download Raspberry Pi Imager https://www.raspberrypi.com/software/
- Install it then start it
- I am selecting Pi3 because that is what I have you can find it written on the pi itself. Hit next
- <img width="684" height="481" alt="01-Pi 3" src="https://github.com/user-attachments/assets/af43924e-892c-41ba-bd3e-6264f09a3be3" />
- Scroll down to "Other specific-purpose OS. Hit Next
- <img width="682" height="481" alt="02-Other Specific-purpose OS" src="https://github.com/user-attachments/assets/630f4c38-f243-43cd-8f3e-23d25bb9803b" />
- Scroll down to "3D printing" Hit next
- <img width="682" height="481" alt="03-3D Printing" src="https://github.com/user-attachments/assets/49b8187d-b351-489e-a78e-ed59c717675c" />
- Scroll down to "Mainsail OS" Hit next
- <img width="682" height="482" alt="04-Mainsail OS" src="https://github.com/user-attachments/assets/63b3fb1e-251a-4afe-8886-de7cf6e36cd7" />
- Select MainsailOS 3.0.0 Raspberry Pi 64
- <img width="677" height="474" alt="05-MainsailOS 3 0" src="https://github.com/user-attachments/assets/a922452c-7298-476b-8917-4955a4de7de6" />
- Choose the SD card installed in your computer
- <img width="677" height="478" alt="06-Storage" src="https://github.com/user-attachments/assets/0de4417c-d187-4626-a3e2-e642a7b8c529" />
- Choose a hostname: this is the name that will come up in your router under device list etc so you can find the ip address
- <img width="680" height="482" alt="07-Hostname" src="https://github.com/user-attachments/assets/61e13f7d-2478-4acd-a3a2-70b7b0634cbc" />
- Set Capital city Time zone and Keyboard
- <img width="684" height="484" alt="08-CityTimeZoneKeyboard" src="https://github.com/user-attachments/assets/03a470f6-3546-4245-bd46-0774866b7323" />
- Username and password
- <img width="683" height="480" alt="09-UserNamePassword" src="https://github.com/user-attachments/assets/a93d9857-5210-440c-ab71-b08fed4335c3" />
- Setup wifi with SSID and password to log onto your lan, make sure this is right as I could not change it when I moved a printer from home to work
- <img width="683" height="481" alt="10-Wifi" src="https://github.com/user-attachments/assets/373335fc-773e-4def-8fff-f58278c29ffb" />
- We will have to SSH into out pi later
- <img width="677" height="482" alt="11-SSH" src="https://github.com/user-attachments/assets/f499abc7-9aaa-47f7-a890-0e99512e3863" />
- Write to the card this will take a while
- <img width="680" height="483" alt="12-Write" src="https://github.com/user-attachments/assets/76406d74-8692-48a3-bf62-98a3b59d4ccd" />
- <img width="684" height="482" alt="13-Writing" src="https://github.com/user-attachments/assets/292b13d4-cdfc-48f5-bf4a-31a03d932ac7" />
Next you can put the card in you pi and plug it in and let it power on.

## Part Two: Configure the Raspberry Pi
- Find the ip address of your pi on your router using the hostname your gave it I used Ender7Red I used that name because I have 3 Ender 7's and I printed the pi cases and screen holders in different colors. If you have the small screen it will tell you what the ip address of the pi is when it starts. Type the ip address into the the address bar of your browser
- <img width="835" height="491" alt="ip address" src="https://github.com/user-attachments/assets/bb2258af-54cd-497b-96cc-f3750f918add" />
- You could used a keyboard and mouse connected to the pi if you have a screen but if you don't you will use the Command Prompt in windows to SSH into the pi to complete the setup. I will use SSH.
- Type: usernam@ipAddress in this case for me it is jpcode@192.168.1.129
- <img width="384" height="95" alt="SSH" src="https://github.com/user-attachments/assets/c8c70b32-1aef-4e28-b02b-0c21d4b116c5" />
- Type "yes" hit enter, enter your password and hit enter and you should see this telling you that you have logged into your pi username@hostname so for me jpcode@Ender7Red
- <img width="780" height="242" alt="password" src="https://github.com/user-attachments/assets/d35a16a0-71e3-4805-a8f2-45fc844a3b83" />








- 







