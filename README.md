## Covid-19 Assessment Bot
The COVID-19 assessment bot is configured using **Microsoft Healthcare Bot** services. 
The bot answers the FAQ's related to COVID-19. [More Info](https://techcommunity.microsoft.com/t5/healthcare-and-life-sciences/updated-on-5-24-2020-quick-start-setting-up-your-covid-19/ba-p/1230537).

The design and code is adjusted to redirect specific questions to appropriate answers. The bot is finally deployed to ***Azure*** and can be embedded in any web app. 

Please ***note that the Azure app service plan costs a lot and the deployment had to be stopped due to a hefty cost.***


## Steps to deploy the Assessment Bot
###### Configuration: 
1. In Azure Marketplace search for "Microsoft Healthcare Bot"
2. Enter the deatils to subscribe to the Bot service.
3. Once deployed, **Go to Resource** and click **Configure Account** and then **Create**. Once configured, click ***Open scenarios template catalog***.
4. Select **COVID-19 Assessment** and then import the template.
5. Under **Manage** in **Scenarios** click the configured bot service.
6. To configure the scenarios for the bot edit the JavaScript code or modify the scenarios in the **Designer** tab which has a friendlier UI.
7. Click **Run** on the top to start the assessment. 

###### Create Webchat Channel:


