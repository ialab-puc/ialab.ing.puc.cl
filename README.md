# Web site of IA-Lab
## Artificial Intelligence Laboratory at PUC Chile
### ialab.ing.puc.cl

#### Installation Instructions

###### Ubuntu

Get the Latest .deb Package of Hugo from Hugo Github Respo 
https://github.com/gohugoio/hugo/releases/

Now Download the Latest release via wget method
'''
wget https://github.com/gohugoio/hugo/releases/download/v0.48/hugo_0.48_Linux-64bit.deb
'''

Extract the downloaded package
'''
sudo dpkg -i hugo_0.48_Linux-64bit.deb
'''

Remove the downloaded package
'''
rm hugo_0.48_Linux-64bit.deb
'''

Verify your Install
'''
which hugo
hugo version
'''

Now run the website locally
'''
hugo server -D
'''

Navigate to the local site at http://localhost:1313/.