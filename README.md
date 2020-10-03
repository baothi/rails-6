# rails-6
# curl https://raw.githubusercontent.com/rails/webpacker/master/lib/install/config/webpacker.yml > config/webpacker.yml 
# bundle exec rake webpacker:install
git config --global user.name "baothi"
git config --global user.email "baothi246@gmail.com"

Create a new repository
git clone git@gitlab.com:baothi/xxxxx.git
cd supply
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Push an existing folder
cd existing_folder
git init
git remote add origin git@gitlab.com:baothi/xxxxxx.git
git add .
git commit -m "Initial commit"
git push -u origin master

Push an existing Git repository
cd existing_repo
git remote rename origin old-origin
git remote add origin git@gitlab.com:baothi/xxxxxx.git
git push -u origin --all
git push -u origin --tags
