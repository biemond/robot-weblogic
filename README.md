#Robot frameworks tests for WebLogic 12.1.3

##WebLogic configuration
- Have a running WebLogic 12.1.3 WebLogic server
- Change the weblogic parameters in the 2 resource.txt files
- Enable RESTful Management Services in the WebLogic console -> Domain -> General -> Advanced

##Test
- pybot console_testsuites
- pybot rest_testsuites

##Documentation
- http://robotframework.org/robotframework/

##Robot framework on Mac
- install homebrew, ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
- install python, brew install python
- install robotframework, pip install robotframework
- verify installation, pybot --version

##robotframework-selenium2library
- https://github.com/rtomac/robotframework-selenium2library

###install
- pip install -U robotframework-selenium2library

##robotframework-requests
- https://github.com/bulkan/robotframework-requests

###install
- pip install -U robotframework-requests

###documentation
- http://bulkan.github.io/robotframework-requests

###examples
- https://github.com/bulkan/robotframework-requests/blob/master/tests/testcase.txt
