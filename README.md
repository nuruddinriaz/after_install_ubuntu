# :house: After install `Ubuntu` you need to do the works below...

## Update apt sources and install software below...
go to terminal > (for all of below)
1. `sudo apt-get update`
2. `sudo apt-get install git`
3. `sudo apt-get install zsh`

## To install `chromium-browser`...
`sudo apt-get install chromium-browser`

## To install a .deb software follow the instruction below...
1. Go to the directory where you saved `.deb` file.
2. `sudo dpkg -i <package-name>`
>ex: `sudo dpkg -i code_1.19.1-1513676564_amd64.deb`

### To run `vs-code` via `terminal`

`code .` + press enter

## To get `sublime-text` in `apt` way follow the instructions below...
1. Install the GPG key:
`wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -`

2. Ensure apt is set up to work with https sources:
`sudo apt-get install apt-transport-https`

3. Select the channel to use:
>Stable
`echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list`

>Dev
`echo "deb https://download.sublimetext.com/ apt/dev/" | sudo tee /etc/apt/sources.list.d/sublime-text.list`

4. Install Sublime Text
`sudo apt-get install sublime-text`

### To `installe packages` for sublime-text
`1. Ctrl+Shift+P 2. Type Package Control: Install package 3. Write package name 4. Press Enter` 
~~~
Necessary packages are (1) 1337 Color Scheme (2) Emmet.
~~~

### To see sublime-text `installed packages`

`Preferences -> Package Control -> List Packages` or `1. Ctrl+Shift+P
2. Type Package Control: Remove Package
3. You see the list of all packages installed`

## To install `node.js`...
`sudo apt-get install node.js`

## To install `npm`...
`sudo apt-get install npm`

# To install xampp in ubuntu...
1. `Go to the directory where you saved .run file.`
2. `sudo chmod +x xampp-linux-x64-7.2.0-0-installer.run`
3. `sudo ./xampp-linux-x64-7.2.0-0-installer.run`

## To run xampp in ubuntu...
`sudo /opt/lampp/lampp start`

## To create a mini-server...
`php -S localhost:2018`
`Here 2018 could be any 4 digit.`

<hr/>

### I'm Nuruddin Riaz
* Mobile: 01814-485 428
* E-mail: nuruddinriaz@gmail.com

* [GitHub](https://github.com/nuruddinriaz)
* [LinkedIn](https://www.linkedin.com/in/nuruddin-riaz-a59960155/)
* [Facebook](https://web.facebook.com/profile.php?id=100002463491827)
* [Twitter](https://twitter.com/nu_riaz28)
* [Instagram](https://www.instagram.com/nu_riaz28/)
