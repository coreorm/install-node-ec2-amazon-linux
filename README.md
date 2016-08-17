# Install NodeJS on amazon linux

Simple steps for installing offical nodejs 4.x

```
sudo yum install git
sudo yum update
curl --silent --location https://rpm.nodesource.com/setup_4.x | sudo bash -
sudo yum -y install nodejs
sudo yum -y install gcc-c++ make
curl --silent --location "https://www.npmjs.org/install.sh" | sudo bash -
```

For deploying, install forever

```
sudo npm install -g forever
```

And that's it.
