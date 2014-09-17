# Website for Startup Speed Dating
* <http://entrepreneur-club.org/>
* <http://ssd.entrepreneur-club.org/>

## How to modify
Clone the repo:

    git clone git@github.com:entrepreneur-club/ssd-website.git
    cd ssd-website
    
Do your modifications.

Then, upload it to the server:

    ssh -p 222 entrepreneur@core.entrepreneur-club.org
    cd /var/www/ssd/
    # ssh agent forwarding must be active for this,
    # and you have to be member in the github
    # ec organisation https://github.com/entrepreneur-club/
    # and your ssh key must be uploaded to github
    git pull

New version is online!

## If you don't know git
Download the website from [here](https://github.com/entrepreneur-club/ssd-website/archive/master.zip).

You can then unzip it, and open and modify `index.html` and add image files etc. When you are finished, zip the file again and send it to an IT committee member with a reference to this instruction.

Please **do not** just save the website from <http://ssd.entrepreneur-club.org/> from your browser and then modify this file, as this will break some links.
