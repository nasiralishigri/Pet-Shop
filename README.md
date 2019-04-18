# Pet-Shop
Block Chain Example
# To Run / Deploy Project on Live 
 Open Git Bash or Window command in your Project Folder
# Run These Commands
 # 1. truffle Compile
                  This compile your Smart Contracts
 # 2- truffle migrate
 # 3- npm run dev
        This Command your project on live server for this we have need some setting 
        
  # Settings
    #   Pakage.json File
          In this file your live server path is found eg. code given below
                                        {
                                  "name": "Voting",
                                  "description": "Voting App",
                                  "authors": "Nasir",
                                  "version": "1.0.0",
                                  "main": "truffle.js",
                                  "dependencies": {
                                      "test": "test"
                                  },
                                  "scripts": {
                                      "dev": "lite-server",
                                      "test": "echo \"Error: no test specified\" && exit 1"
                                    }
                              }

when You run this your project live but Show Error Cannot GET /
The File with code setting given below to solve this issue

  # bs-config.js
        This file give the path of your source file where your html css Js file exist.
        eg. code given below
                                  {
                            "server":{
                             "baseDir": ["./src", "./build/contracts"]
                           }
                          }
                          
   Now all is working You perform every Action with front and backend Smart Contract through Web3.js file in JS language...
