---
type: rule
archivedreason: 
title: Do you automate the generation of your API specification and required clients?
guid: 83b61858-d33b-40cb-ae0e-4bb8ba301e3b
uri: automate-the-generation-of-your-api-specification-and-required-clients
created: 2019-05-25T01:58:58.0000000Z
authors:
- title: Adam Cogan
  url: https://ssw.com.au/people/adam-cogan
related: []
redirects:
- do-you-automate-the-generation-of-your-api-specification-and-required-clients

---


<p>If your changes to your WebAPI break your client, then you want to know right away.<br></p><p>Using NSwag you should generate your API client eg. Angular Client.<br></p><ul><li>You run nswag.exe on the post-build event<br></li><li>Nswag will generate the client code and update the API client file directly<br></li></ul>
<br><excerpt class='endintro'></excerpt><br>
<dl class="goodImage"><dt>​<img src="using-nswag-helps-automation.jpg" alt="using-nswag-helps-automation.jpg" /></dt><dd>Figure: Good example – using NSwag config file helps with automation. Since the API client is generated automatically next time we build, any breaking changes will be obvious immediately<br></dd></dl><p>Now this is automated this is no longer a concern we need to deal with.<br></p><p><b>More info:</b> 
      <a href="http://www.codingflow.net/building-single-page-applications-on-asp-net-core-2-1-with-angular-6-part-3-implementing-open-api/">http://www.codingflow.net/building-single-page-applications-on-asp-net-core-2-1-with-angular-6-part-3-implementing-open-api/</a>​</p>

