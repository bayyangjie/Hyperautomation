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
![Image 2](https://github.com/bayyangjie/Hyperautomation/blob/main/Visuals/zapier1.png?raw=true) <br> <br>
![Image 3](https://github.com/bayyangjie/Hyperautomation/blob/main/Visuals/zapier2.png?raw=true) <br> <br>
![Image 4](https://github.com/bayyangjie/Hyperautomation/blob/main/Visuals/zapier3.png?raw=true) <br> <br>
![zaptest](https://github.com/bayyangjie/Hyperautomation/assets/153354426/f9cdd945-a84c-4443-ac44-4f80eed723d6) <br> <br>


ASANA project management: <br> <br>
![Image 5](https://github.com/bayyangjie/Hyperautomation/blob/main/Visuals/asana1.png?raw=true) <br> <br>
![Image 6](https://github.com/bayyangjie/Hyperautomation/blob/main/Visuals/asana2.png?raw=true)



