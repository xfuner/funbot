# What is Funbot
Funbot is a AI bot customization and dialogue platform, users are able to create AI bots based on specific knowledge library, with certain system presets and human settings. By utilizing the capabilities of large language models, it achieves information retrieval, analysis, and logical reasoning. 
![image](https://github.com/xfuner/funbot/assets/145464942/4db019f4-bd08-41fd-9651-fb3d96f6a08c)

# How to create a bot
1. Click "+" icon and enter the creating page
![image](https://github.com/xfuner/funbot/assets/145464942/dae52cf4-0e16-4811-b5dd-0807d523213a)

2. Fill in the fields in the creation form

# Bot Attributes

1. Basic Information

- **Name**: The name of the robot, displayed on the homepage and conversation page

- **Introduction**: A short introduction of the robot

- **Long Description**: A detailed description of the robot's functions

- **Greeting**: The first greeting of your robot when a user starts a conversation for the first time

- **Category**: Choose a category for the robot

- **Avatar**: The avatar displayed for the robot

- **Voice**: Select a voice when the robot's messages are played as audio


2. Permission Settings

- **Access Permissions**:

**Public** All Funbot users can chat with the robot

**Private**: Private robot, by default only you can chat with it, you can authorize others by sharing the robot on the conversation page

3. Dataset and Dialogue Settings

**Knowledge Library**: The knowledge base for the robot to learn from, supporting Feishu space, Google Docs, and Google Sheets

	💡 You should grant access permission to Funbot account for the document before importing (add fp-platform-docs@funplus-user-center.iam.gserviceaccount.com as Viewer)

**System Prompt**: Set the robot's context, norms or constraints, basic settings, personality, etc. through System Prompt

**Sample Learning**: Provide a dataset of question and answer pairs to train the robot to better answer questions in the way you expect

**Question Example**: Provide question examples for users to help them understand the questioning method

4. Advanced Configuration

**Multiple Rounds of Dialogue**: The number of context lines the robot understands, between 0-20.

**Temperature**: Control the randomness of the robot's answers. Between 0-2

**Model Version**: ChatGPT version, default is 3.5
