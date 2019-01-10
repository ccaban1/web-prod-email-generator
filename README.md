# Email Generator
### Email Template
Use of this box is optional. It’s a place to put the email template code from the shell in the Cheetahmail app.

### Image Name
Paste the first image name into this box. Any additional images will be found automatically as
long as the images adhere to the following naming convention:
W_X_Y-Z
1. W is the week number for the email
2. X is the name of the email, and should match what it is called in the Google Doc including the date at the beginning
3. Y is a number determines the order the images appear in the email from top to bottom (and left to right for side-by-side CTAs)
4. Z is a number determines which link will be applied to the image according to the order of the links pasted in the link box

Example: 11_042318_AWESOME_EMAIL_3-2
This image is for a week 11 email, will be the third image in the email and will link to the second link in the link list

**Notes**
1. Do not include the file extension when pasting in the file name
2. If a link should go to the Print Pass, element Z of the naming convention should be replaced with the letter ‘P’ instead of a number, and the numbering should continue as normal. 

### Links
Paste the links for the email in this box. Links should be separated by line breaks. Any excess space around the links will be cleaned up by the script.

Relative links will automatically be attached to http://www.lordandtaylor.com. Absolute links will be inserted into the email as is.

Print Pass links do not nee

### Add Banner
The Add Banner button creates additional fields for adding image names in order to accommodate banners with different file names than the body into the email. The banner image names should still use the same naming convention outlined above with the numbering kept separate from the rest of the email.

**Example**:
If the first image in the email is 11_042318_AWESOME_EMAIL_1-1, the first image for a banner appearing in the email should be 11_042318_GREAT_BANNER_1-1. Links for the banner should go into the Links text area in the same order as the associated
images. If the banner goes above the main body of the email, the banner links should be above the email body links in the text box.

###Auto-fill
The Auto-fill button will automatically find and add any banners associated with the email in the Google Doc, as well as fill out the linking for the email and all associated banners.

**Notes***
1. Auto-fill will not work if an email requires pulling elements from some other emails
2. Atypical or non-standard information or requests in Prod Notes on the Google Doc may cause Auto-fill to fail
3. In the event that Auto-fill encounters a problem, it will alert you, and you should still be able to fill out the information manually

### Generate Email
The Generate Email button will run the script, which takes the links and image names and creates properly formatted tables for the email code. This includes adding the height and width parameters, adding any animated gifs, and formatting tables with side-by-side CTAs.

**Notes**:
1. The script cannot handle text boxes or barcodes in emails


##Additional Information

###Print Pass

**Naming**
If an email contains a print pass link, the final number in the naming convention (Z in the explanation above) should be replaced by the letter ‘P’ with the numbering resuming where it left off after that if applicable.

Example:

In an email with three links, the second of which goes to the print pass, the image names should look like this:
11_042318_AWESOME_EMAIL_1-1
11_042318_AWESOME_EMAIL_2-P
11_042318_AWESOME_EMAIL_3-2


**Linking**
You do not need to include the print pass in the list of links for an email. If the email generator detects that there is a print pass link in the email, it will find the correct print pass link for that email and apply it automatically. However, you may add a print pass link anywhere in the Links text box and it will be used instead of the detected link.

**Important**: If you do not use the proper naming convention as outlined above, print pass links will not be properly applied for your email
