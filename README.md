# Visitor Management

The Visitor Management is a collection of four Power Apps to manage smart factory visitors. 
* Visitor Welcome Desk app located at the entry point of the factory floor
* Visitor Self Registration app on a tablet device
* Visitor Management app to manage visits
* Visitor Mixed Reality app to confirm mixed reality competency

![Image of Visitor Management](/images/SwissSmartFactoryVisitorManagementApps.png)

We build this apps during a three day Hackathon with the Swiss Smart Factory team.

[Hackathon - Visitor Management app](https://www.teamruegg.com/blog/posts/2021/september/visitor-management/)

## Swiss Smart Factory 
The Swiss Smart Factory (SSF) is the first test and demonstration platform for Industry 4.0 in Switzerland and with the lighthouse project «Drone Production», we intended to show how smart factories can already work today with an entire production ecosystem powered by Microsoft Cloud and our Partner ecosystem.

* [Switzerland Innovation - Swiss Smart Factory lighthouse project](https://www.sipbb.ch/en/forschung/swiss-smart-factory/)
* [Swiss Smart Factory powered by Microsoft Cloud](https://www.teamruegg.com/digital/smart-factory/)


## Applications
### Visitor Self Registration app - Welcome Desk
The Welcome Desk application is a self-service application manage smart factory visitors and their equipment loans, like Tablet or HoloLens during the visit.
New visitors can self register at the Visitor Welcome Desk by check-in and selecting the guest host, entering their contact data and selecting a loan equipment to be used during their visit. After their visit, they can check-out and return loaned equipment. 

To ensure safety work rules during their stay, the app captures a photo of the visitor and using Azure Custom Vision model to check, if the visitors is equipped with Hard Hat and Mask.

### Visitor Self Registration app - Tablet
Similar to the Welcome Desk but optimized on Tablet devices.

### Visitor Management app
The Visitor Management app is used by the guest hosts to manage visits, visitors and equipment loans.

### Visitor Mixed Reality experience confirmation app
Visitors who loan a HoloLens device during their visit and experience the mixed reality scenario using Dynamics 365 Guides, can earn after successfully finish a guided scenario, the Swiss Smart Factory Mixed Reality badge.

## Prerequisites

The Visitor Management app is build on Power Platform and Azure Custom Vision. And therefor the following apps needs to be installed and configured before deploying the app:
* Microsoft Dataverse environement
* Azure Subscription for Azure CustomVision
