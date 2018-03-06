# packages

# build package
dpkg-deb --build helloworld_1.0-1

# install package 
dpkg -i helloworld_1.0-1.deb

# list package
sudo apt list --installed
