# Assignment

Assumtions:-

              ->  Have an ssh connection established with the deployment server.
              ->  CMake already installed in the server
Explanation:-

              ->Script_build
                  Clone the git to the local server
                  Compile and build the project in the local server
                  Copy artifact and Script_deploy.sh to deployment server
                  Run the Script_deploy.sh in the deployment server

              ->Script_deploy
                  Install libevent package in the deployment server
                  Compile and Insall hiredis in the deployment server
                  Start redis server
                  Run artifact
