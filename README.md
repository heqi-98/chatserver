# environment:linux (ubuntu)
# install g++:
sudo apt-get install g++
# install cmake:
sudo apt-get install cmake
# install boost:
sudo apt-get install libboost-dev libboost-test-dev #(required) 
sudo apt-get install libcurl4-openssl-dev libc-ares-dev #(not required) 
sudo apt-get install protobuf-compiler libprotobuf-dev #(not required) 
# install muduo library:
git clone https://github.com/chenshuo/muduo.git
cd muduo
./build.sh
# install redis
sudo apt-get install redis-server
# install mysql
sudo apt-get install mysql-server