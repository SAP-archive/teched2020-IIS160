# Exercises - IIS160

Run the following exercises to complete the hands-on:<br><br>

## Reserving an Exercise User

- Open the [**User Registration Self-Service**](https://iis160-dispatcher.cfapps.eu10.hana.ondemand.com/users/iis160/reserve) for the hands-on session. A PDF document with the session details is automatically downloaded.<br><br>
![](images/Self-Service-01.png)<br><br>
- With the user details provided you can log on to all systems required in this hands-on session.<br><br>
![](images/Self-Service-02.png)<br><br><br><br>


## Creating the Workflow Instance

- Open the [**IIS160 Launchpad**](https://flpnwc-adc04c831.dispatcher.hana.ondemand.com/sites/teched-launchpad) in Google Chrome and logon with the reserved user from the previous exercise [Reserving an Exercise User](#reserving-an-exercise-user).<br><br>
- Choose the **Workflow Creation** tile.<br><br>
![](images/CIAS-01.png)<br><br>
- The **Create Workflow** application opens in a new browser tab.<br><br>
- The **Integration Scenario** parameters are already pre-selected for this hands-on. Therefore, simply choose **Step 2** to continue.<br><br>
![](images/CIAS-02.png)<br><br>
- On the **Integration Landscape** step, select **SFPART056049** as **SAP SuccessFactors Employee Central instance** [1], **V0386** as **SAP Cloud Platform Integration tenant** [2] and **S4H** as **SAP S/4HANA On-Premise system** [3].<br><br>
- Choose **Review** [4] to continue.<br><br>
![](images/CIAS-03.png)<br><br>
- **Review** your selections on the **Summary** screen and choose **Generate Workflow**. The workflow will be generated and activated for the user reserved in the step [Reserving an Exercise User](#reserving-an-exercise-user).<br><br>
![](images/CIAS-04.png)<br><br>
- Once the **Workflow** is ready you will see a success message on the screen.<br><br>
- Choose **Cloud Integration Automation Service Inbox** link to start.<br><br>
![](images/CIAS-05.png)<br><br><br><br>


## Running the Workflow in the Cloud Integration Automation Service

- Open the [**Cloud Integration Automation Service**](https://cias-buoxpnldir.dispatcher.hana.ondemand.com/index.html) in Google Chrome and logon with the reserved user from the previous exercise [Reserving an Exercise User](#reserving-an-exercise-user).<br><br>
- Choose **My Inbox**.<br><br>
![](images/CIAS-06.png)<br><br>
- The first workflow task is loaded. Read the **Disclaimer** carefully and choose **I Agree** to continue.<br><br>
- In the **Confirm System Components** task, identify the **SAP Cloud Platform Integration** system and assign the destination **CPI_V0386** to the field **Assign Destination**.<br><br>
![](images/CIAS-07.png)<br><br>
- Scroll down to the **SAP S/4HANA System** and switch the **Access Option** from **Via SAP Logon** to **Via Host**.<br><br>
![](images/CIAS-08.png)<br><br>
- Finally, set the **Have you checked the pre-requisite for ABAP Automation?** option to **Yes**.<br><br>
![](images/CIAS-09.png)<br><br>
- Choose **Confirm Systems** and continue with the instructions given in the workflow.<br><br><br><br><br><br>


## Important
Please observe the following notes when executing the workflow:<br>

#### Automated Task Execution
- Please ensure that you always execute the automation using **Execute Step** [1] before you complete a task using **Task Completed** [2].<br><br>
![](images/CIAS-10.png)<br><br>
