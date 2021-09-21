---
nav_title: Contact Cards
article_title: Contact Cards
page_order: 3
description: "This reference article covers how to create a Contact Card to include in your MMS and SMS messages."
page_type: reference
channel:
  - MMS
  
---

# Contact Cards 

> Contact Cards (sometimes known as vCard or Virtual Contact Files (VCF)) are a standardized file format for sending business and contact information that can be easily imported into address books or contact books. 

Contact Cards can be created [programmatically](https://www.twilio.com/blog/send-vcard-twilio-sms) and uploaded to the Braze [Media Library]({{site.baseurl}}/user_guide/engagement_tools/templates_and_media/media_library/#media-library) or created through our built-in Contact Card Generator. You can assign common properties to these cards, such as your company's name, phone number, address, email, and a small photo.

## Contact Card Generator
![Contact Card Composer]({% image_buster /assets/img/sms/contactcards.gif %}){: style="max-width:75%;margin-top:15px;"}

### Step 1: Assign Name

Contact Cards can be created from the SMS and MMS composer. Select the __Contact Card Generator__ tab to get started.

Next, you will be prompted to input your company name or nickname. This is the name that your users will see when they save the card. A 20 character limit is enforced to ensure the user can see your whole company name or alias in their contacts and messaging app. 

![Contact Card Composer]({% image_buster /assets/img/sms/contact_card1.png %})

### Step 2: Assign Phone Number

Select the subscription group and desired phone number from the available drop-down options. This number will be listed in your Contact Card and available on their phone to text to once saved.

Note that alphanumeric codes are not compatible with two-way messaging and are not supported for Contact Cards.

### Step 3: Optional Fields
![Contact Card Options]({% image_buster /assets/img/sms/contact_card2.png %}){: style="float:right;max-width:35%;margin-left:15px;"}

__Contact Card Contact Photo__<br>
You can upload an optional thumbnail contact photo for your Contact Card. We recommend a 240x240 jpeg or png image. Any high-resolution images uploaded will be resized to 240x240 to ensure the deliverability of your message, as MMS messages larger than 5MB may fail.

__Other Information__<br>
Other fields allow you to insert your name, subheader, address, and other contact information that your user may want to have handy. 

<br>

### Step 4: Saving your Contact Card

Once you've input all the necessary fields, click __Generate Contact Card__, and it will be automatically attached to your campaign or Canvas. From here, you can add a message, test your Contact Card, and launch your campaign or Canvas.

The Contact card will also be saved in the [Media Library]({{site.baseurl}}/user_guide/engagement_tools/templates_and_media/media_library/#media-library) to easily reuse in future campaigns and Canvases.

## Adding an Existing Contact Card

To add an existing Contact Card, create a campaign or Canvas and select your desired subscription group. Next, an __Add Media__ option will appear in the message composer window. Here, you can upload an existing Contact Card file or locate one through the Media Library.