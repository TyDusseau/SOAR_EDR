# SOAR EDR 

## Objective

The objective of my SOAR EDR cybersecurity project was to improve threat response by integrating a cloud-based PC with automation tools. Using Limacharlie for endpoint detection and Tines for automation, the system managed events from the cloud PC. When an alert was triggered, users were asked if they wanted to isolate the PC. If they chose to do so, the system automatically isolated the PC and sent a confirmation message; if not, it just sent a notification. This approach aimed to speed up responses and ensure clear communication during security incidents.

### Skills Learned

- **Endpoint Detection and Response (EDR) Configuration:** Proficient in setting up and managing Limacharlie for effective endpoint monitoring.
- **Automation with Tines:** Skilled in creating and implementing automated workflows to streamline incident management.
- **Integration of Communication Tools:** Experienced in using Slack and email for real-time alerts and notifications.
- **Cloud-Based Security Management:** Knowledgeable in managing and responding to security events from a cloud-based PC environment
- **User Interaction and Decision Handling:** Capable of designing systems that prompt users for decisions and automate actions based on their responses.

### Tools Used

- Limacharlie: Endpoint Detection and Response (EDR)
- Tines: Automation and workflow management
- Slack: Real-time alerts and communication
- Email: Notifications
- Cloud-Based PC: Event generation and management

## Steps
![Screenshot 2024-08-10 123523](https://github.com/user-attachments/assets/45ad801e-ac6d-4d76-85d2-ac1382285de0)

_**Ref 1:** Generated playbook diagram in Draw.io_

-----

![Screenshot 2024-08-10 132509](https://github.com/user-attachments/assets/cc3ccf84-7f42-4dae-ad0c-948c983bb22c)
![Screenshot 2024-08-10 132312](https://github.com/user-attachments/assets/0706ae9f-8759-4561-96de-544cc0fde875)

_**Ref 2:** Spun up cloud PC and installed LimaCharlie_

-----


![Screenshot 2024-08-10 134926](https://github.com/user-attachments/assets/a46cb9b0-1e4c-44f6-9f23-1581f4f3df62)

_**Ref 3:** Ran LaZagne to generate telemtry via LimaCharlie_

-----

![Screenshot 2024-08-10 135058](https://github.com/user-attachments/assets/ee0156d3-99b1-43e2-8109-221e3659825e)

_**Ref 4:** Viewed generated telemetry in LimaCharlie to verify proper configuration_

-----


![Screenshot 2024-08-10 141011](https://github.com/user-attachments/assets/47d2da1e-a01b-4a91-bfe2-677d1250f46e)

_**Ref 5:** Created custom detection rule for the HackTool_

-----

![Screenshot 2024-08-10 141418](https://github.com/user-attachments/assets/de9e9c89-64ec-4b79-a561-ae975dfbb066)
![Screenshot 2024-08-10 142030](https://github.com/user-attachments/assets/c49b1967-0732-4b4c-a88e-ebf91f1ec11a)

_**Ref 6:** Verified detection worked as expected_

-----

![Screenshot 2024-08-10 142337](https://github.com/user-attachments/assets/56b62cfc-1732-4bab-83cb-192adf3704fa)
![Screenshot 2024-08-10 144501](https://github.com/user-attachments/assets/d02f3eda-8b22-4206-9d68-4f3c1ac45f0e)

_**Ref 7:** Created a Slack channel for alerts and connected it to Tines_

-----

![Screenshot 2024-08-10 160812](https://github.com/user-attachments/assets/c202f8cc-b551-46ef-ab32-3a39c7ee184e)

_**Ref 8:** Built out reamining automation in Tines_

-----

![Screenshot 2024-08-10 161236](https://github.com/user-attachments/assets/f80ee853-08b8-4858-8d45-e2038ec2c572)
![Screenshot 2024-08-10 161244](https://github.com/user-attachments/assets/6e258a64-fe9b-4b0f-80cf-71fdf990ce50)

_**Ref 9:** Examples of messages/notifications generated from Tines automation_

-----

![Screenshot 2024-08-10 155659](https://github.com/user-attachments/assets/c8a0ea74-7244-441e-9860-a98fb15799c9)

_**Ref 10:** User prompted to make decision about potentially infected PC with relevant info included_

-----

![Screenshot 2024-08-10 172617](https://github.com/user-attachments/assets/04e6820a-51b3-405c-8b45-1e651aa32747)
![Screenshot 2024-08-10 161303](https://github.com/user-attachments/assets/68671521-985f-4974-be14-8d0a5008c16a)

_**Ref 11:** Messages sent from Tines to Slack after yes/no decision from prompt above_

-----

![Screenshot 2024-08-10 155709](https://github.com/user-attachments/assets/c2455308-2977-4b8b-b43d-b34d1952eec3)
![Screenshot 2024-08-10 155744](https://github.com/user-attachments/assets/1a29b149-c9bf-4283-8168-b56efd11f7a4)

_**Ref 12:** Infected computer successfully isolated via automation_












