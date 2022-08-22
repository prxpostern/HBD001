HerokuBannedDeployer
IT IS MANDITORY TO FORK THIS REPO
With this you can deploy repos that are banned/blacklisted by heroku in different platforms

Deploy From Here
Railway
Deploy on Railway

Heroku
Deploy

Note:
You need to set the vars manually or use local_config

For Private Repos
1️⃣ Generate PAT from github
Go to "Settings"
Scroll down then go to "Developer settings"
Press "Personal access tokens" then press "Generate new token"
Fill "Note" then check "repo"
If "repo" is not checked, you cannot clone a private repository.
Scroll down then press "Generate token"
Finally, a PAT is generated. Copy it
2️⃣ Create repo url with PAT
Goto this repl
Fork It
Edit Secrets (Environment variables)
PAT - Give above generated PAT value there
REPO - Give your private repo url
Save and Run the Code
Copy the Generated Url from the Console
You can also manually generate the link
It should be in the below format

https://<pat>@github.com/<your account or organization>/<repo>.git
3️⃣ Deploy using the above Generated Url
