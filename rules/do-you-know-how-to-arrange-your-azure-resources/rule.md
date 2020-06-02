---
type: rule
archivedreason: 
title: Do you know how to arrange your Azure resources?
guid: 2c2f55d2-66fd-4c29-a7cb-6598c54b60df
uri: do-you-know-how-to-arrange-your-azure-resources
created: 2020-06-02T20:48:06.0000000Z
authors:
- id: 1
  title: Adam Cogan
- id: 78
  title: Matt Wicks
- id: 60
  title: Anthony Nguyen
- id: 32
  title: Mehmet Ozdemir
related: []

---


There is no cost saving to group databases into on single resource group. It is better to provision the database in the same resource group as the application that uses it.​<br>
<br><excerpt class='endintro'></excerpt><br>
<dl class="badImage">
   <dt>​<img src="/PublishingImages/arrange-azure-resources-bad.jpg" alt="arrange-azure-resources-bad.jpg" style="width&#58;750px;" /></dt><dd>Figure&#58; Bad example - SSW.SQL has all the Databases for different apps in one place<br></dd></dl>

