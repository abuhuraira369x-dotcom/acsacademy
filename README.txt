ACS Academy Admin Files

Upload the folders exactly as they are:

admin/index.html
admin/config.yml
content/homepage.md

Then commit and wait for Netlify to deploy.

Important:
For /admin/ login to work, enable Netlify Identity and Git Gateway.

Netlify:
Site configuration -> Identity -> Enable Identity
Identity -> Registration preferences -> Invite only
Identity -> Services -> Enable Git Gateway

Then open:
https://acsacademyh.netlify.app/admin/
