<h1>Lab 1B: Creating our First Resource: Storage Account</h1>
This tutorial outlines the general account structure of Microsoft Azure and how to create a Tenant (Organization) account, Subscription and Resource Groups. Importantly, labs 1 throuth 7 will be conducted using virtual environments within Azure, so this Lab 1A is foundational as we progress through the other labs.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute) accessed via the web

<h2>Operating Systems Used </h2>

- MacOS Monterey v12.6.1 on Macbook M1 Pro</b>

<h2>List of Prerequisites</h2>

- Computer with Internet connection
- Credit card (required even for free Azure credits)

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/unyXSfO.png" height="80%" width="80%" alt="Lab 1A: Azure Structure Overview"/>
</p>
<p>
Before we dive into specifics, the graphic above illustrates the Tenant/Subscription/Resource Group structure within Microsoft Azure. A Tenant account in  Azure is your organization's master account encompassing all services and billing. A Tenant can have multiple Subscriptions, which is primarily a way to segregate billing into, for example, different departments. Within each Subscription, multiple Resource Groups can be created to house or compartmentalize the various Azure services your organization may require.
</p>
<br />

<p>
<img src="https://i.imgur.com/XZlTglI.png" height="80%" width="80%" alt="Lab 1A: Azure search free account"/>
</p>
<p>
Now, let's set up a free Azure acccount. Use a browser to search for something like "free azure account" and look for the right link. 
</p>
<br />

<p>
<img src="https://i.imgur.com/hSPnVzW.png" height="80%" width="80%" alt="Lab 1A: Azure Start free"/>
</p>
<p>
A note about the $200 free Azure credits. It is free in Azure to create a Tenant account, Subscriptions and Resource Groups. However, when you initiate a service that puts resources to work, such as a storage account or virtual environment, charges begin to accrue based on the type and amount of resources used charged by Azure. The purpose of this turorial is to walk through the steps in a lab environment and then, once done, delete any resources as quickly as possible to minimize charges against our $200 credit. Furthermore, the credit is good for 30 days. After 30 days you can "pay as you go" for resources used or make a new Tenant account with a new email and credit card.
</p>
<br />

<p>
<img src="https://i.imgur.com/6rsTPDd.png" height="80%" width="80%" alt="Lab 1A: Azure MS sign in"/>
</p>
<p>
Sign in using your Microsoft account, create a new Microsoft account, or other sign in options.
</p>
<br />

<p>
<img src="https://i.imgur.com/f3FijvS.png" height="80%" width="80%" alt="Lab 1A: Azure Profile"/>
</p>
<p>
Fill out the Profile section. The second part of this section will require a credit card.
</p>
<br />

<p>
<img src="https://i.imgur.com/M5Ta9th.png" height="80%" width="80%" alt="Lab 1A: Azure Get started"/>
</p>
<p>
Your account is now set up. Click the link to go to the Azure portal at portal.azure.com.
</p>
<br />

<p>
<img src="https://i.imgur.com/C949OpZ.png" height="80%" width="80%" alt="Lab 1A: Azure Quickstart"/>
</p>
<p>
Personally I prefer the Home page vs the Quickstart page. If you're like me, click Home. On the Home page you will see the link back to the Quickstart page.
</p>
<br />

<p>
<img src="https://i.imgur.com/Or7TCI8.png" height="80%" width="80%" alt="Lab 1A: Azure Navigate"/>
</p>
<p>
On the Home page there are several ways to navigate. Personally I gravitate to a quick search, but there are a variety of ways to find what you need. Explore!
  
  Note here that when we created our Tenant, a Subscription account was created automatically (Azure subscription 1). Let's click this link to verify and explore our Subscription.
</p>
<br />

<p>
<img src="https://i.imgur.com/WTj6OwZ.png" height="80%" width="80%" alt="Lab 1A: Azure Subscription"/>
</p>
<p>
On our "Azure subscription 1" page, we can find just about anything about this Subscription on the menu along the left side, including activity, access, security, costs and billing, settings and support. From this page we can also rename or cancel this Subscription. Although we could simply search from this page for our next task (to create a Resource Group), let's click Home.
</p>
<br />

<p>
<img src="https://i.imgur.com/rft57g3.png" height="80%" width="80%" alt="Lab 1A: Azure Resource Groups"/>
</p>
<p>
Now that we have a Tenant account and an active Subscription, we need a Resource Group within which we will later add the Resource we want to actually use (for the purposes of this lab, a Storage Account). A Resource Group is a collection of Resources that share the same lifecycle, permissions and policies. To create a Resource Group, search or click Resource Groups.
</p>
<br />

<p>
<img src="https://i.imgur.com/ouYix5D.png" height="80%" width="80%" alt="Lab 1A: Azure Create Resource Group"/>
</p>
<p>
From the Resource Groups page, click Create Resource Group.
</p>
<br />

<p>
<img src="https://i.imgur.com/yDW7PVf.png" height="80%" width="80%" alt="Lab 1A: Azure Resource Group review and create"/>
</p>
<p>
From the Create a Resource Group page: 1) select the right Subscription, 2) name this Resource Group, 3) select a region (ideally near you) and 4) click Review and Create. Add Tags for better tracking on an interim screen if you wish.
</p>
<br />

<p>
<img src="https://i.imgur.com/JoxyTPv.png" height="80%" width="80%" alt="Lab 1A: Azure Resource Group created"/>
</p>
<p>
Resource Group created. Click the link for details of this Resource Group.
</p>
<br />

<p>
<img src="https://i.imgur.com/zWhTexq.png" height="80%" width="80%" alt="Lab 1A: Azure Resource Group detail"/>
</p>
<p>
The Resource Groups page allows you to select the Resource Group you wish to work with, then view and configure parameters and settings.
  
  This concludes the lab. With our Tenant account, Subscription and Resource Group in place, we are now ready to add Resources in the next lab.
</p>
<br />
