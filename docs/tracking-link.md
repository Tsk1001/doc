
To get a Tracking URL for a publisher, you should go to: *browse all > Advertiser Campaigns > choose your campaign  and you can find the Tracking URL in the information about advertiser campaign.Or if you create a new advertiser campaign the system will generate a tracking URL automatically.

Tracking URL will look like:
http://dev-edge.adrout.net/red?cid=101



The Tracking URL contains couple of parts and each of them are important:

*	edge.adrout.net - this is the tracking domain 
*	red – this part tells the server to request the redirect through our service.
*	cid=101 – Campaign ID is the ID of  AD campaign, that signifies that the click should be associated with this campaign on conversion. 101 is the example of unique identifier to Ad campaign.

In addition, you have an opportunity to add other parameters, such as:

*	tid=10101 – Transaction Id is the optional parameter , that provide the unique identifier of transactions, 10101 – is the example of an identifier.
*	uaid=10-76-38 – User advertising ID is the optional parameter that provides the unique identifier of the user for advertisers. 10-76-38 – is the example of identifier. This parameter depends on device platform, for example:  
   1.	for apple this parameter called as IDFA  and it will be look like: AEBE52E7-03EE-455A-B3C4-E57283966239.  
   2. For google this parameter called as Google AID and it will be look like: 4c30c866-30d6-4418-a6dc-0f702747bf58
   3.	For Microsoft this parameter called as Windows Advertising Identifier and it will be look like :  776c5de673d2c4n6c8828v27s7382dh3
*	ref=yourcompany – Referrer is the optional parameter, that provide the information about the resource (for example: website or app) on which your APP is promoting. Yourcompany – is the example of referrer. In case of app-to-app model in referrer should be the name of package – the unique APP identifier. The app identifier would be different for each device platform, for example:
   1.	For apple it would be look like: A1B2C3D4E5.domainname.applicationname
   2.	For google it would be look like : com.game.plane.client
   3.	For Microsoft it would be look like : 965722bc-t087-5a77-abab-121c2b43202e

In case of web-to-app model in referrer should be the URL from the website, for example: www.website.com
