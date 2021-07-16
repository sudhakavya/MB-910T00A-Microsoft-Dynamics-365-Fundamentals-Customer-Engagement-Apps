---
lab:
    title: 'Lab 2.1: Create and manage a Lead in Dynamics 365 Sales'
    module: 'Module 2: Learn the Fundamentals of Dynamics 365 Sales'
---

Module 2: Learn the Fundamentals of Dynamics 365 Sales
========================

## Practice Lab 2.1 - Create and manage a Lead in Dynamics 365 Sales

## Objectives

During this exercise, you will be capturing a sales lead for Suzanne Burke. She recently reached out to you and is interested in some of your organization’s products and services. Not only will you be capturing the lead in the system, but you will be using the tools available in Dynamics 365 Sales to work the lead through the qualification process.


## Lab Setup

  - **Estimated Time**: 15 minutes

## Instructions

1. Open the **[Dynamics 365 Sales Trial](https://dynamics.microsoft.com/en-us/dynamics-365-free-trial/)** link. 

    >Note: If Required, You will find Dynamics 365 Sale below, and click on **Try for Free** then Enter the **work email address** as provided in the Environment Details to start your **free trial** and Click on **Start Your free trial**, Then Select your **country** and Enter the **Phone Number**,  Click on **Next**. Else **Skip**.

   ![](images/Mb910Lab.png)
 
1. Click on **Sales trial** on the top Left.

   ![](images/Lab-01.png)
 
1. In Dynamics 365 Apps, you will find **Dynamics 365 Sales Hub**. Click on **Dynamics 365 Sales Hub**.

   ![](images/Lab-02.png)
   
1. Using the navigation on the left side of the screen, select **Leads**. 

1. From the **My Open Leads** view, Select the **New** button on the Command bar.

   ![](images/Image-03.png)  

1. Complete your new lead record as follows:

	- **Topic:** Looking for New Equipment – Your Initials

	- **First Name:** Suzanne

	- **Last Name:** Burke

	- **Job Title:** CFO

	- **Business Phone:** 888 555-8715

	- **Email:** Suzanne@contososample.com

	- **Company:** Contoso - Washington

	- **Street 1:** 1989 Smith Ave

	- **City:** Seattle

	- **State/Province:** WA

	- **ZIP/Postal Code:** 98001 

   ![](images/Image-05.png)  

1. Select the **Save** button on the Command Bar to save the new the Lead and leave it open. 

   ![](images/Image-04.png)  

1. Notice the **Lead to Opportunity** Business Process Flow at the top of the record. Click the **Qualify Stage** to select it. Complete the stage as follows:

	- **Purchase Timeframe:** This Quarter

	- **Estimated Budget:** 25000 

	- **Purchase Process:** Individual

	- **Identify Decision Maker:** Completed

   ![](images/Image-06.png) 

1. Go to the **Record Timeline** in the middle of the screen and click the **Plus Sign Icon** to add a new activity. 

   ![](images/Image-07.png) 

1. From the menu that appears, select **Phone Call**.

   ![](images/Image-08.png)

1. On the **Quick Create Phone Call** screen, set the **Subject** field to **Initial Phone Call** and leave the rest of the information as is. 

1. Click the **Save and Close** button.

   ![](images/Image-09.png)

1. Notice the **Initial Phone Call** activity is now displayed on the **Record Timeline**. Over the activity and select the close activity **Check Mark Icon** to mark the phone call as completed.
 
   ![](images/Lab-03.png) 

1. On the **Close Phone Call** window, select the **Close** button 

   ![](images/Image-12.png)

1.  Next you will qualify the lead record. This will create a related Opportunity record[1] and move to the next stage[2] of the Lead to Opportunity sales process. On the **Command Bar**, select the **Qualify** button.
   
      ![](images/Image-18.png)

1. After the system qualifies the lead, a new Opportunity record will be created, and the business process will advance to the **Develop** stage. Select the **Qualify** stage to view the original lead record. 
