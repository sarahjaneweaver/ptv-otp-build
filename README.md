# ptv-otp-build
Scripts to build an OTP instance using PTC GTFS data


What you need

1. a UNIX - tested on OSX and Ubuntu so far

2. a JDK - tested with Oracle JDK 8u45 


Basic first time usage instuctions

1. clone this repo

2. swicth to the directory containing the repo

3. edit the files and set an appropriate BASE_PATH

3. run 'bootstrap'

4. wait while the script pulls down a bunch of stuff and builds an OTP graph

5. point your browser to localhost:8080 when you see the Grizzly Server running message

6. use it


Starting the server after you've run the boot strap

1. swicth to the directory containing the repo

2. run 'startServer'

3. point your browser to localhost:8080 when you see the Grizzly Server running message

4. use it