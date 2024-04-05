virtualenv venv
source venv/bin/activate

git init
git add .
git commit -m "First commit"
git remote add origin https://github.com/andreichiro/snowflake-aws.git
pbcopy < ~/.ssh/insert_your_key_here.pub
git push -u origin master


