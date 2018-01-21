# ElectraTweakInstaller

This is in bash, so linux and MacOS (and unix) or use bash for windows.
This is just a simple tool I made for myself, you can use it too!

Dependencies:
curl
tar
sshpass

to verify if you have the dependencies:
1- open termial
2- type curl --help
3- you will get the help file of curl then you are ok
4- type tar
5- you will get : tar: Must specify one of -c, -r, -t, -u, -x (then you are good)
6-type sshpass: you will get the help file (probably not cause you did not install it yet :p)


To use the app, you need to install the dependencies, to do so you need Homebrew (https://brew.sh)
1- open terminal
2- type: /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
3- follow the installation instructions
4- once installed you can pass to install the dependencies
5- install sshpass: brew install https://raw.githubusercontent.com/kadwanev/bigboybrew/master/Library/Formula/sshpass.rb
6- run the application 

using the app: 
1- Launch tweak_installer 
2- choose your .deb file
3- type your ip address
4- type your password, the default is alpine
5- enjoy





you can also sue the script, Script Usage:

./search_and_download_tweak.sh name-of-tweak-to-search

./install_script.sh nameOfDeb.deb ip.of.your.iphone

Thanks to cydiaupdates.org for providing a source to download deb files.
Thanks to r/reddit for the google spreadsheet of compatible tweaks:)

PRs are always welcome!
If someone want to create an app for it, it will be the best. I don't have the time right now to do it.
