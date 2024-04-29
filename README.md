<img src="images/box-dev-logo-clip.png" 
alt= “box-dev-logo” 
style="margin-left:-10px;"
width=40%;>

# Box AI + Box Skills Metadata Extraction Demo
This is a demo of a Box Skill using Google Cloud Platform to host the serverless function and Box AIs metadata extraction service.

**Note: You will need to add a gcp crendentials file and update the serverless.yml with that appropriate connection information.**

## Steps to Setup and Deploy

0. You will need to set up a Box Skill in the Box Developer Console, as well as authorize the skill and configure a folder to watch for uploads. You can find out more about that process in our [developer documentation](https://developer.box.com/guides/applications/custom-skills/setup/). 
1. Install Node v18.18.0 or higher
2. [Set up a Google Cloud Account](https://serverless.com/framework/docs/providers/google/guide/credentials/)
3. Download the code.
4. Add your google keyfile to the .gcloud folder and name it serverless.json.
5. TBD