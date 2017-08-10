![] (https://s3.amazonaws.com/spotify-audio-files/large-icon.png)
# Alexa-Skill-Music-Nerd-Trivia

Are you a music nerd? Can you quickly recognize a song and guess the artist?
This Alexa Custom Skill will put your knowledge to the test!

Technologies Leveraged
-----------------------
* **Alexa Skills Kit**
* **AWS Skills Kit**
* **AWS Lambda**
* **AWS DynamoDB**
* **AWS S3**
* **NodeJS**

After completing this tutorial, you will know how to:

  * **Create a parameter-based skill** - This tutorial will walk first-time Alexa skills developers through all the required steps involved in creating a parameter-based skill using a template called ‘Reindeer Trivia’.
  * **Understand the basics of VUI design** - Creating this skill will help you understand the basics of creating a working Voice User Interface (VUI) while using a cut/paste approach to development. You will learn by doing, and end up with a published Alexa skill. This tutorial includes instructions on how to customize the skill and submit it for certification. For guidance on designing a voice experience with Alexa you can also [watch this video](https://goto.webcasts.com/starthere.jsp?ei=1087592).
  * **Use JavaScript/Node.js and the Alexa Skills Kit to create a skill** - You will use the template as a guide but the customization is up to you. For more background information on using the Alexa Skills Kit please [watch this video](https://goto.webcasts.com/starthere.jsp?ei=1087595).
  * **Get your skill published** - Once you have completed your skill, this tutorial will guide you through testing your skill and sending your skill through the certification process, making it available to be enabled by any Alexa user.

# Let's Get Started

## Step 1. Setting up Your Alexa Skill in the Developer Portal

Skills are managed through the Amazon Developer Portal. You’ll link the Lambda function you created to a skill defined in the [Developer Portal](https://developer.amazon.com/).

1. Navigate to the Amazon Developer Portal. Sign in or create a free account (upper right). You might see a different image if you have registered already or our page may have changed. If you see a similar menu and the ability to create an account or sign in, you are in the right place.

 ![](https://s3.amazonaws.com/spotify-audio-files/small-image.jpeg)
 ![](https://s3.amazonaws.com/lantern-code-samples-images/trivia/devsignin.png)

2. Once signed in, navigate to Alexa and select **"Getting Started"** under Alexa Skills Kit.

 ![](https://s3.amazonaws.com/lantern-code-samples-images/trivia/Getstartedask.png)

3. Here is where you will define and manage your skill. Select **"Add a New Skill"**

 ![](https://s3.amazonaws.com/lantern-code-samples-images/trivia/AddnewSkill.png)
