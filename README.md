# TwitterBotDetection

## Project Goals/Overview

The purpose of this project was to use labeled spambot or real user data for twitter users to identify if a user was real or a bot. In order to access data for this project labeled data was used from The Bot Repository (https://botometer.iuni.iu.edu/bot-repository/index.html). Using the user_id's the twitter API was then used to gather user and twitter data.

The final presentation can be found in the file 'Final_Presentation.pdf' or from this link: https://www.canva.com/design/DADzFVFyV1w/EKallOqTxcx5imXVGGgeFQ/view?utm_content=DADzFVFyV1w&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink

### Python Notebook Descriptions

1. 'TwitterAPI.ipynb' - For the users that didn't come with any data, I needed to access the data via the Twitter API. This notebook goes through and accesses user data as well as actual tweet data for those users also.
2. 'TwitterDataCleanUsers.ipynb' - Engineering features and cleaning data notebook for UserData
3. 'Combining_Tweets.ipynb' - This notebook is just merging the given tweets with the additional tweets that I accessed from the API.
4. 'TwitterModels.ipynb' - Final notebook for running models
