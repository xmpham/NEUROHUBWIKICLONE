Need access to the [UKBiobank data](https://www.ukbiobank.ac.uk/about-biobank-uk/)? Please follow the steps below.

McGill University and the UK Biobank Limited have signed a Material Transfer Agreement (MTA) that allows McGill researchers to use the UK Biobank Resource for specific, select projects. New Applicant Researchers can be added to the application, and request access to the UK Biobank Resources, by completing the following steps

**Please note: all steps must be followed in sequence and each one confirmed as successfully completed before proceeding to subsequent steps**

## Procedure to access data:

![](https://github.com/neurohub/neurohub_documentation/blob/master/images/ukb_flowchart.png)

#### 1.Getting a UK Biobank Account [UK Biobank Access Management System (AMS)](https://bbams.ndph.ox.ac.uk/ams/). 

##### UK Biobank Access Management (AMS) - what you need: 
- Be sure to specify your McGill affiliated email address when completing your registration. 
- Some patience (Once processed, registrations will be confirmed by email from the UK Biobank and may take up to two weeks to complete.)
- It is of great importance to choose “McGill University” as your “name of primary institute” from the drop-down menu, otherwise your account 
  cannot be linked to your LORIS account later on.

![](https://github.com/neurohub/neurohub_documentation/blob/master/images/login_ams.png)

- Once processed, registrations will be confirmed by email from the UK Biobank


#### 2.Getting a LORIS Account 
**To complete this step you first need the registration confirmation from the UK Biobank!**
- fill in the LORIS Users Consent and Agreement form
 - read the Material Transfer Agreement [MTA] (https://ukb-covid.loris.ca/login/request-account/?download=mta)


Detailed instructions regarding the registration process are available here.
Once processed, registrations will be confirmed by email from the UK Biobank and may take up to two weeks to complete.

**For those users with an existing UK Biobank account please ensure to add McGill University as your current institutional affiliation.**

#### 2. Complete and agree to the terms of the [User Consent & Agreement Form](https://ukb-covid.loris.ca/login/request-account/) specific to the McGill agreement with the UK Biobank.

This step and the collection of the required information is necessary so as to confirm the details of your UK Biobank registration, and to verify eligibility to access the data as part of the approved application.

Once reviewed and approved, users will be added to the associated McGill UK Biobank application. Users will receive an email from the AMS system notifying them of the status and updated affiliation with the McGill UK Biobank application.

#### 3. At this step, users are entitled to access the UK Biobank data through the McGill agreement. Access is managed by the NeuroHub team and at present is possible though two resource points:

   1. The [NeuroHub](https://neurohub.ca/index.html) Platform, which is a core facility of the [Healthy Brains, Healthy Lives (HBHL)](https://www.mcgill.ca/hbhl/) initiative. NeuroHub brings together established data and computational infrastructure with new technologies to provide a web-based platform to support scientific research in neuroinformatics, genomics, social sciences, biology, among others.

   2. The [Compute Canada](https://www.computecanada.ca/home/) National Platform system of [Béluga](https://docs.computecanada.ca/wiki/B%C3%A9luga/en), with the UK Biobank data managed on that platform by the NeuroHub team.

Further information regarding both processes are described below. 

<p>&nbsp;</p>

**_NeuroHub registration process_**

Visit the [NeuroHub portal](https://neurohub.ca/index.html), and [request an account]() if needed.

i. Account requests will be confirmed by email once created within the NeuroHub portal. For new account requests please ensure to use your McGill email address which would have been used for your registration with the UK Biobank.

ii. If you already have a [CBRAIN](http://www.cbrain.ca/) account, it will work with NeuroHub.

iii. At this time, the NeuroHub portal is available in the Alpha release phase. As such, you must be connected to the McGill VPN in order to access the NeuroHub portal. The portal will be made more broadly accessible once early-user testing is completed and the portal subsequently put into full production.

iv. Login to the NeuroHub portal and go to the Projects tab. Under the list of Projects you will see the datasets associated with the UK Biobank. Dataset files can be downloaded via the NeuroHub portal for analysis on your local system. Additional data processing capabilities will soon be added directly into the NeuroHub portal.

<p>&nbsp;</p>

**_Compute Canada - Beluga registration process_**

i. [Apply for a Compute Canada account](https://www.computecanada.ca/research-portal/account-management/apply-for-an-account/) if you do not already have an account. The above link provides detailed information about how to apply for a Compute Canada account.

   * Select the “Register” action from the front-page of the Compute Canada Database (CCDB)
   * Complete the registration procedure specifying your Institution, Department and Position details.
For the “Sponsor” information you must specify the CCRI (Compute Canada Role Identifier) of your immediate supervisor (Faculty Member). This information will be available from your supervisor. It will look like (abc-123-12). If you are a Faculty member, alternate information will be requested.

**Once you have received confirmation that your Compute Canada registration has been completed and approved by your immediate supervisor, or if you already have a Compute Canada account, proceed to next step.**

ii. Request access to the UK Biobank Compute Canada data sharing group.

   * Send an email to ukbiobank.neurohub@mcin.ca with the Subject: “**NeuroHub Compute Canada Access Request**” and the body of the email containing the value of your CCRI, as well as your first and last name. Please ensure to send the email from the McGill email address with which you have registered to the UK Biobank.

   * Your CCRI (Compute Canada Role Identifier) can be determined by:

        * login to the Compute Canada Database (CCDB)
        * your CCRI is indicated in bold and is of the form abc-123-12

iii. Once approved, you can access the UK Biobank data on the Béluga computing system of Compute Canada. Access to Béluga is possible via SSH to `beluga.computecanada.ca`. These data are provided “as-is” and are located within the following NeuroHub directory:

`/project/rpp-aevans-ab/neurohub/ukbb/`

   * **Please note**: Only users who have successfully completed the full steps of the registration process and have been approved by the NeuroHub team will be enabled to access the UK Biobank data on Béluga. Access controls are in place which restrict access to the UK Biobank data such that only users who have been authorized to join the data sharing group may access the data.
