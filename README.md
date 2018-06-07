# Email Generator
### Email Template
Use of this box is optional. It’s a place to put the email template code from the shell in the Cheetahmail app.

### Image Name
Paste the first image name into this box. Any additional images will be found automatically as
long as the images adhere to the following naming convention:
X_[image name]_Y-Z
1. X is the week number for the email, and is necessary if the image is animated
2. Y is a number determines the order the images appear in the email from top to bottom (and left to right for side-by-side CTAs)
3. Z is a number determines which link will be applied to the image according to the order of the links pasted in the link box

Example: 11_042318_AWESOME_EMAIL_3-2
This image is for a week 11 email, will be the third image in the email and will link to the second link in the link list

**Note**: Do not include the file extension when pasting in the file name

### Links
Paste the links for the email in this box. Links should be separated by line breaks. Any excess space around the links will be cleaned up by the script.

Relative links will automatically be attached to http://www.lordandtaylor.com. Absolute links will be inserted into the email as is.

### Add Banner
The Add Banner button creates additional fields for adding image names in order to accommodate banners with different file names than the body into the email. The banner image names should still use the same naming convention outlined above with the numbering kept separate from the rest of the email.

**Example**:
If the first image in the email is 11_042318_AWESOME_EMAIL_1-1, the first image for a banner appearing in the email should be 11_042318_GREAT_BANNER_1-1. Links for the banner should go into the Links text area in the same order as the associated
images. If the banner goes above the main body of the email, the banner links should be above the email body links in the text box.

### Generate Code
This button will run the script, which takes the links and image names and creates properly formatted tables for the email code. This includes adding the height and width parameters, adding any animated gifs, and formatting tables with side-by-side CTAs.

**Notes**:
1. The script cannot handle text boxes or barcodes in emails
