virtualenv venv
source venv/bin/activate

git init
git add .
git commit -m "First commit"
git remote add origin https://github.com/andreichiro/snowflake-aws.git
pbcopy < ~/.ssh/id_ed25519_github.pub
git push -u origin master

