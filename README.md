# Installing rails
1. Install curl

If you are running Ubuntu or any debian based distro run

`sudo apt-get install curl`

2. Install rvm

`$ \curl -L https://get.rvm.io | bash -s stable --ruby`

3. Run command as login

Follow [this link](https://rvm.io/integration/gnome-terminal#integrating-rvm-with-gnome-terminal) to enable this feature then restart your terminal before proceeding

4. Install nodejs

`sudo apt-get install nodejs`

5. Install nokogiri and bundler gems

`rvm gemset list`

confirm that global and default gemsets are present

`rvm gemset use global`

`gem install bundler`
`gem install nokogiri`

