## Installation

### Requirements
* [Node.js](https://nodejs.org/en/)



### For Windows machine:
  - Clone the deliverable git repository on your machine
  - Download the latest version of Node.js from [https://nodejs.org/en/](https://nodejs.org/en/) and Install it.
  - If your machine’s 8081 port is free go inside  **<deliverable git folder>/deliverable_editor/** and open **run.bat** file and it will show up that **‘Please go to localhost:8081 ’**
  - Now open browser and go to localhost:8081 and enjoy the deliverable editor.
  - If your 8081 port is busy and ‘STEP 3’ didn’t work for you, Open CMD change directory to **<deliverable git folder>/deliverable_editor/** and execute below two commands
    * **SET PORT=<give any free port no>eg. 8082**
    * **node index.js**
    
    It will show either
**‘Please go to localhost:8082‘**
   or
**‘8082 port already in use, please specify another port’**
  If the port is already in use. In that case please execute above two commands with different port number.


### For Linux based machine:
  - Clone the deliverable git repository on your machine
  - Download the latest version of Node.js from [https://nodejs.org/en/](https://nodejs.org/en/) and Install it.
  - Open terminal and change directory to **<deliverable git folder>/deliverable_editor/**
and execute following command:
    * **node index.js**
    
    It will show either : **‘Please go to localhost:8081‘** or **‘8081 port already in use, please specify another port’** If the 8081 port is busy, execute these commands
    * **Export PORT=<Free port no.> eg. 8082**
    * **node index.js**

    If the port is already in use please execute above two commands with different port number.


### Docker

```sh
**docker build -t image_name <docker_file_path>**
**docker run -it -v <path to content folder>:/content -p <Expose port>:8081 image_name**
```