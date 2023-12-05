# displaysensordata
![Namnlöst diagram drawio (1)](https://github.com/Prsoderlund/displaysensordata/assets/114224908/712c84ad-7fd5-4c33-8c24-5a1a2cba00a9)

______________________________________________________________________________________________________________________________________________________

Raspberry Pi - Connection String:
Description: Utilized a virtual Raspberry Pi along with a connection string to connect to the IoT Hub.
Purpose: Provided an efficient and straightforward method for testing Azure functionality.

![image](https://github.com/Prsoderlund/displaysensordata/assets/114224908/6a84735d-0ae2-4174-a075-7a99cffb1e77)
![image](https://github.com/Prsoderlund/displaysensordata/assets/114224908/98196d2b-a9a7-465d-ad9e-3b7bf720732b)


______________________________________________________________________________________________________________________________________________________

Azure IoT Hub Device - Raspberry Pi - Connection String:
Description: Used Azure IoT Hub to establish secure and reliable communication between the IoT application and devices.
The virtual Raspberry Pi served as the connected device.
Purpose: Ensured a secure and reliable connection between the IoT application and the virtual Raspberry Pi.

![image](https://github.com/Prsoderlund/displaysensordata/assets/114224908/3e5efd11-e29f-461e-a98a-05880c1e1626)
![image](https://github.com/Prsoderlund/displaysensordata/assets/114224908/718362d5-752a-43a4-84d5-c1f7012949e2)

______________________________________________________________________________________________________________________________________________________

VSCode - IoT Hub Monitor Built-in Event Endpoints in JSON:
Description: Used VSCode to monitor built-in event endpoints in JSON format.
Purpose: Enabled real-time monitoring of data transmission from the virtual Raspberry Pi to the IoT Hub.
Facilitated live tracking of data, addressing the challenge of understanding the content of transmitted data during the virtual Raspberry Pi's runtime.

![image](https://github.com/Prsoderlund/displaysensordata/assets/114224908/e0238d0d-40df-41d0-b36b-e04b33cd4a76)

______________________________________________________________________________________________________________________________________________________

Azure Stream Analytics Job - Datastream:
Description: Employed Azure Stream Analytics for real-time analysis of streamed data.
Configured input (Raspberry Pi from iot hub) and output (Power BI) within the Stream Analytics job.
Manually connected to the workspace and created a dataset with a table.
Purpose: Enabled real-time analysis of data generated by the virtual Raspberry Pi.
Provided a cloud-based platform for easy configuration and scalability of the stream analytics job.
Used Azure Stream Analytics and Datastream to stream data to Power BI, facilitating the creation of powerful real-time dashboards and visualizations.

![image](https://github.com/Prsoderlund/displaysensordata/assets/114224908/b2ae97a9-39e7-4f33-9ce4-26dea2711b9a)
![image](https://github.com/Prsoderlund/displaysensordata/assets/114224908/f017e8e5-3264-4289-96e0-b9dc8a10072c)
![image](https://github.com/Prsoderlund/displaysensordata/assets/114224908/10cd8652-080d-400c-93c6-939f6b7fdd19)
![image](https://github.com/Prsoderlund/displaysensordata/assets/114224908/3033ea15-e914-4b7f-a996-fef9ea2ad5d2)

______________________________________________________________________________________________________________________________________________________

Power BI - Workspace, Report, and Data Visualization:
Description: Chose Power BI for simple data visualization from the virtual Raspberry Pi.
Created a Power BI workspace, report, and extracted data from the dataset and table generated by Azure Stream Analytics.
Purpose: Selected Power BI for its simplicity in visualizing data from the virtual Raspberry Pi.
Facilitated the creation of powerful real-time dashboards and visualizations using the streamed data from Azure Stream Analytics and Datastream.

![image](https://github.com/Prsoderlund/displaysensordata/assets/114224908/012e0575-a56a-4a42-9dc3-3ce0004b0320)

______________________________________________________________________________________________________________________________________________________

Integrera väderdata från API till Power BI för visualisering. 
Använd Postman för att verifiera att väderdata från API är korrekt, av god kvalitet och har rätt format.

![image](https://github.com/Prsoderlund/displaysensordata/assets/114224908/7896f9d8-8233-4bf2-9f2b-07857e43a5aa)
![image](https://github.com/Prsoderlund/displaysensordata/assets/114224908/0769e7fd-c48c-424c-9d78-058c2d705a85)



