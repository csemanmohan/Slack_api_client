# Slack_api_client - Slack application integrated with ChatBot-EndPoint.
Slack api integration with chatbot Endpoint-Python.

Easy way to integrate any application like chatbot with slack application.
I recommend to follow this as personally i have faced some challenges while using slack-client web api.

Slack community keeps this under category of Slack RTM(Real Time Messaging) API.
for reference- https://api.slack.com/rtm

INSTALLATION PROCESS-
> Please do execute the command- 
      pip install -r requirements.txt # Make sure requiremnt.text is copied and kept on CWD.
      
> Declare URL and Slack_token parameter here-
      6. # 'url', chatbot endpoint and 'slack_token' is slack application user-access-token
      7. url = "http://127.0.0.1:####/########/v2/###"
      8. slack_token = "xoxb-###########-############-##################8hoI"
      NOTE :- https://api.slack.com/apps, use this link create new application, you will get token
      
> Run the application -
      python slack_rtm_client.py
      
###########################################################################################
TEST-
      Create a new slack channel, invite your application(for which, you mentioned the token)
      and type-
              [@app_name input_text] 
              eg- 
              User- @chatbot hi
              Bot- Hello i am your Chatbot, How can i help you.
