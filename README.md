# TEST REPO INITIALIZED #


*The flow:*

1. git pull
2. git status
3. git add README
4. git commit -m "removed the X. lines"
5. git push 


Ruby via RVM for Ubuntu:
  sudo apt-get install bash curl git
  sudo apti-get install build-essential bison openssl libreadline6 libreadline6-dev curl git-core zlib1g zlib1g-dev libssl-dev libyaml-dev libsqlite3-0 libsqlite3-dev sqlite3 libxml2-dev libxslt-dev autoconf libc6-dev

  bash < <(curl -s https://rvm.beginrescueend.com/install/rvm)

  vi ~/.bashrc  

Then append to end of that file:

  [[ -s "$HOME/.rvm/scripts/rvm" ]] && source "$HOME/.rvm/scripts/rvm" 

Open a new terminal and type:
  rvm install 1.9.2
# hopefully that works
  rvm use 1.9.2 --default

