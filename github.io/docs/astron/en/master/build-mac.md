I highly recommand you install brew it makes installing astron and its depepdencies easier. 
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
run that in terminal
after that run brew install  yaml-cpp boost cmake
then after that do these linux instructions
"After setting up your environment you can compile with any of the following:

For release:

cmake -DCMAKE_BUILD_TYPE=Release . && make
For development (with Trace and Debug messages):

cmake -DCMAKE_BUILD_TYPE=Debug . && make
For development (without Trace and Debug messages):

cmake . && make"