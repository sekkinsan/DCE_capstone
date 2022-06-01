# DCE_capstone
DCE Capstone project for NA PSS team members: Talia Hoffman, Meena Ramamoorthy, Jacob Yun, Jessica Zajac

## Capstone Project #1: Document Remediation 

### Customer problem to be solved 
<p>Pebble Pharma is a pharmaceuticals company that has struggled to modernize their onboarding process for their new hires. Historically they send multiple onboarding agreements through email and their homegrown HR system. They want to modernize this process through a front end system that tracks their entire employee journey. In addition to Adobe Acrobat Sign, they have also purchased AEM Assets, Sites and Forms. </p>

<p> Additionally, they are prioritizing accessibility of their documents. This is a companywide initiative at Pebble, particularly after an external audit revealed that they do not meet accessibility standards in multiple areas of their processes. </p>

<p> Remediation team is tasked with mass remediation effort for key HR and legal documents </p>


### Methodology 

![Fast Start Methodology](/assets/fast_start_methodology.JPG)


### [PDF accessibility report of poorly tagged file](https://github.com/sekkinsan/DCE_capstone/blob/main/Pebble_Pharm_201X_Benefits.pdf.accreport.html) 

#### Document Issues
<p> Tagged PDF - Failed -  The document isn't tagged to specify the correct reading order. </p>
<p> Logical Reading Order - Needs Manual Check - Reading order always needs to be manually verified by a person. </p>
<p> Title - Failed - The document was missing a title. </p>
<p> Color contrast - Needs Manual Check - Document may contain content that isn't accessible to people who are color-blind.</p>

#### Page Content Issues

##### Tagged content
<p> Element 1 not tagged and not shown within the Tags tree or Content section.</p>
<p> Element 2 not tagged and not shown within the Tags tree or Content section.</p>
<p> Element 3 not tagged and not shown within the Tags tree or Content section.</p>
<p> Element 4 not tagged and not shown within the Tags tree or Content section.</p>

##### Tab order
<p>Page 1-7 tab order failed since tabbing should lead the reader in logical reading order.</p>

#### Alternate Text

##### Figures alternate text
<p>Figures 1-11 do not have alternate text or are not set up as artifacts.</p>

##### Other elements alternate text
<p>Elements 1 & 2 do not have alternate text or are not set up as artifacts.</p>

#### Tables

##### Headers
<p>Elements 1-8 are missing headers.</p>

##### Summary
<p>Elements 1-8 are missing summaries.</p>

### Remediation plan 
  1. Verified that the PDF was not created from a scanned image 
  2. Verified that the PDF contained fillable form fields and added those form fields within Acrobat 
  3. Verified that the PDF contained links and added those links to direct recipients correctly 
  4. Verified that the PDF did not contain multimedia 
  5. Analyzed the document elements 
  6. Tagged the document and set the reading order 
  7. Ran multiple iterations of the accessibility checker within Acrobat and revise as needed 


### [PDF accessibility report of remediated file](https://github.com/sekkinsan/DCE_capstone/blob/main/Pebble_Pharm_201X_Benefits_remediated.pdf.accreport.html) 

#### Page Content Issues

##### Tagged content
<p> Element 1 not tagged and not shown within the Tags tree or content section. (page 5) </p>

##### Tagged annotations
<p> Element 1 (link) not tagged. (page 2) </p>
<p> Element 2 - 13 (table cells) marked as annotation and not tagged. (page 4)</p>

#### Tables

##### Headers
<p> Element 1 is missing headers. (page 4) </p>

##### Regularity
<p> Table has 2 rows with 3 columns, and 2 rows with 2 columns. Typically tables are evenly distributed throughout. (page 8) </p>


### Delivery workflow 

  ![Delivery Workflow](/assets/delivery_workflow.JPG)


### Customer outcome and value realized 
<p> Utilizing a front end system and having it seamlessly integrated with Adobe Acrobat Sign and AEM created a consolidated system for Pebble Pharm. This new system resulted in a 1-hour time savings for each benefit packet that's being sent out to new employees. </p>

<p> We made many improvements on meeting the accessibility standards for this 201X benefit packet. Unfortunately, the accessibility report does show some issues that were unresolved. Without the source document, full remediation was not possible. With that being said, customer is satisfied with the results with the improvement of user experience for those using assistive tools. The HR team is setting the precedent for other teams to prioritize PDF accessibility within the company, since this engagement ultimately elevated their candidates' user experience. </p>


### Future automation 

![Future Automation](/assets/future_automation.JPG)
