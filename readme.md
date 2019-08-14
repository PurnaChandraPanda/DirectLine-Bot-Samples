# Flow

There are just few points to consider here:
1.	You have bot service application deployed as "web app bot" or "bot channels registration" resource.
2.	For that bot resource, have DirectLine channel enabled.
3.	Copy the DirectLine secret key.
4.	Update the key in client side (web or desktop app), and hit bot service application.

## Why DirectLine?

DirectLine channel alone does not have any UI, in comparison to other available channels, such as: Teams, Skype, WebChat, etc.. And, primary purpose of DirectLine channel is to enable custom 
channels with custom UI to-and-fro for bot service application via DirectLine secret key.