## Project Objectives

### Objective 1
- Designed and constructed a workflow that employed UiPath automation to receive an input (i.e a click, a trigger, capture an image or text etc.), auto evaluate the data, and then provide an output to address an enterprise function problem.

#### What was done
- Designed a use case where input is collected and generated the desired output.
- The use case here was using UiPath Automation Cloud app to design a customer feedback survey form and one that could serve as a base template for future modifications or for reusability purposes
- The fields in the form included the creation of text boxes for user text input and form header label, adding event rules for the URL link, creation of button features for selecting options in a question

### Objective 2
- Designed and evaluated a full automation solution through the use of various business process automation applications, from identifying problems to data collection, automation, and visualisation.
- Created a test use case scenario whereby users with access to a shared document on ServiceNow database will get notified by email trigger notifications whenever there are updates to the database in ServiceNow. The aim was to allow for more efficient documentation as well as tracking of record updates by each user.

#### What was done
- Cleaned the dataset using Excel such as handling blank entries, ensuring data consistency such as capital letters and timestamp formats
- Imported the cleaned dataset into ServiceNow system
- Set up a connection between ServiceNow and Zapier platform which creates a further linkage to Outlook email which is responsible for receiving the notification triggering.
- Employed ASANA to create a project management schedule from initialization to development and finally to the deployment phase

Created a ServiceNow production table 'shipmentstbl' that the loaded dataset would be imported into: <br> <br>
![Image 1](https://github.com/bayyangjie/Hyperautomation/blob/main/Visuals/tabletransform.png?raw=true) <br> <br>

Created staging table ‘shipments1stag’ to store the dataset before importing it into the target table: <br> <br>
![Image 7](https://github.com/bayyangjie/Hyperautomation/blob/main/Visuals/stagingtbl.png?raw=true) <br> <br>

Transformation mapping: <br> <br>
![Image 8](https://github.com/bayyangjie/Hyperautomation/blob/main/Visuals/transform.png?raw=true) <br> <br>

ServiceNow and Zapier connection: <br> <br>

Connection setup between zapier and servicenow: <br>
![connection](https://github.com/bayyangjie/Hyperautomation/assets/153354426/02020b7f-0627-40f7-b61b-8256ec02f612) <br> <br>

Loading the servicenow table in zapier: <br>
![loadtblzap](https://github.com/bayyangjie/Hyperautomation/assets/153354426/db0093fa-7125-49d3-9f0c-534115d749f9)

A new test record that was created in the Servicenow production table 'shipmentstbl' shows up in the test step in zapier: <br>
![newrecordzap](https://github.com/bayyangjie/Hyperautomation/assets/153354426/bbe121cf-b791-4bda-9fc2-f4b0b53e99c7) <br>

Entering email addresses that will be receiving the ZAP & giving a subject header for the ZAP: <br>
![setuptestzap](https://github.com/bayyangjie/Hyperautomation/assets/153354426/ed5a3b02-8428-4cdd-aa39-ff080d6893ca) <br>

Setting the body format and create sample email format to test the ZAP email trigger: <br>
![notifyformat](https://github.com/bayyangjie/Hyperautomation/assets/153354426/7a48f2bf-f451-433c-8caf-a9ff3d5ed45e) <br>

Sent the test step to the email address: <br>
![sendtestzap](https://github.com/bayyangjie/Hyperautomation/assets/153354426/d4c5cdbe-0c13-4efc-a3d5-f30f60081fb9) <br>

Receive notification email about a new record created in servicenow production table 'shipmentstbl': <br>
![receivenotfiy](https://github.com/bayyangjie/Hyperautomation/assets/153354426/778e0e57-22e8-41cc-8f15-ee800e577ee1) <br>


ASANA project management: <br> <br>
![Image 5](https://github.com/bayyangjie/Hyperautomation/blob/main/Visuals/asana1.png?raw=true) <br> <br>
![Image 6](https://github.com/bayyangjie/Hyperautomation/blob/main/Visuals/asana2.png?raw=true)



