# :house: After install `Ubuntu` you need to do works below...

## Update apt sources and install software below...
go to terminal > (for all of bwlow)
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

# To install xampp on ubuntu...
1. Go to the directory where you saved .run file.
2. `sudo chmod +x xampp-linux-x64-7.2.0-0-installer.run`
3. `sudo ./xampp-linux-x64-7.2.0-0-installer.run`

## To run xampp in ubuntu...
`sudo /opt/lampp/lampp start`

## To create a mini-server...
`php -S localhost:2018`

<hr/>

### I'm Nuruddin Riaz

E-mail: nuruddinriaz@gmail.com

* [GitHub](https://github.com/nuruddinriaz)
* [LinkedIn](https://www.linkedin.com/in/nuruddin-riaz-a59960155/)
* [Facebook](https://web.facebook.com/profile.php?id=100002463491827)
* [Twitter](https://twitter.com/nu_riaz28)
* [Instagram](https://www.instagram.com/nu_riaz28/)
