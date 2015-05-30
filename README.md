# ptv-otp-build
Scripts to build an OTP instance using PTC GTFS data


=== WHAT YOU NEED ===

1. a UNIX - tested on OSX and Ubuntu so far

2. a JDK - tested with Oracle JDK 8u45 


=== FIRST TIME USAGE ===

1. clone this repo

2. swicth to the directory containing the repo

3. edit the files and set an appropriate BASE_PATH

3. run 'bootstrap'

4. wait while the script pulls down a bunch of stuff and builds an OTP graph

5. point your browser to localhost:8080 when you see the Grizzly Server running message

6. use it


=== STARTING A SERVER LATER ===

1. swicth to the directory containing the repo

2. run 'startServer'

3. point your browser to localhost:8080 when you see the Grizzly Server running message

4. use it


=== FURTHER READING ===

http://www.opentripplanner.org


