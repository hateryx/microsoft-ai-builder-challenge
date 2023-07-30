## AI Builder Text Recognition

-   With the help of Azure Computer Vision OCR service technology, AI Builder Text recognition will try to identify printed or handwritten text in images or documents.

    -   Only English texts are supported
    -   Must be in JPG, PNG, BMP, TIFF and PDF file format

-   Business problems solved with the app

    | Scenario Category                         | Example                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
    | ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | <h3>Assisted Typing</h3>                  | Front line workers will take a picture of a product or an object that contains an identifier or a price. This information can be used to update and/or retrieve information from Microsoft CRM. <br><br><b>[Example]</b><br>`A car rental company's employee takes pictures of cars during checkout to report damage. The agent takes the picture, which is then processed by AI Builder to extract the car license plate number. This number is used to get information about the car into CRM and to display it to the agent. The agent records damage on the car, records the returned date, and then updates CRM.` |
    | <h3>Person or product presence check</h3> | Front line workers take a picture of a person or an object that contains an identifier. This information can be used to confirm the presence. <br><br><b>[Example]</b><br>`An airport uses pilots' cards to confirm that they are boarding the correct flight. Airport staff will take a picture of the pilot's card, which is processed by AI Builder to extract the pilot's identifier. This identifier is used to get information about the pilot's incoming flight, check consistency with the pilot's presence, and confirm access.`                                                                              |
    | <h3>Automated data entry</h3>             | Agents take pictures of paper forms that contain records. This information is automatically entered into CRM. <br><br><b>[Example]</b><br>`A public company is auditing pharmacies. The auditors go on site and use a paper form to record results. Afterward, an agent manually enters the results in CRM. The agent takes a picture of each audit record and saves it in a folder. A flow processes all new pictures in the folders, sends them to AI Builder to extract the audited notes, and then saves them in CRM`                                                                                              |

## Build a Power Automate flow with AI Builder Text recognition

Reference <a href="https://learn.microsoft.com/en-us/training/modules/get-started-with-ai-builder-text-recognition/3-build-flow">here</a>

-   Create a Dataverse table to store recognized text
-   Set the folder that Power Automate will monitor for new incoming images
-   Call AI Builder Text recognition
-   Save the result in the table that you previously created
-   Save the results to the table

## Build a Power Apps application that uses AI Builder Text recognition

Reference <a href="https://learn.microsoft.com/en-us/training/modules/get-started-with-ai-builder-text-recognition/4-build-application">here</a>

-   Create an application in Power Apps
-   Show results of model’s extracted information
-   Retrieve the list of all text lines and display it to the user
-
