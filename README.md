# steps for installing haraka on a DO droplet

Create DO droplet Ubuntu 16.04.4 x64 and ssh into it

Install and update node and npm
```
sudo apt-get update
sudo apt-get install nodejs
sudo apt-get install npm
sudo npm install -g n
sudo n stable
```
Install haraka

`npm install -g Haraka`

Ensure you're in home directory and make a directory to store haraka files in
```
cd
mkdir haraka
```
Create haraka instance in the new haraka directory

`haraka -i haraka` 

Start the service 

`haraka -c haraka`
