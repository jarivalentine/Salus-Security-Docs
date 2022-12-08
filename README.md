# ![Salus Security](./images/logo_salus.png)
### Client badges
![vulnerabilities](https://sonar.ti.howest.be/api/project_badges/measure?project=2022.project-ii:mars-client-11&metric=vulnerabilities)
![code_smells](https://sonar.ti.howest.be/api/project_badges/measure?project=2022.project-ii:mars-client-11&metric=code_smells)
![bugs](https://sonar.ti.howest.be/api/project_badges/measure?project=2022.project-ii:mars-client-11&metric=bugs)

![duplicated_lines_density](https://sonar.ti.howest.be/api/project_badges/measure?project=2022.project-ii:mars-client-11&metric=duplicated_lines_density)
![coverage](https://sonar.ti.howest.be/api/project_badges/measure?project=2022.project-ii:mars-client-11&metric=coverage)

### Server badges

![vulnerabilities](https://sonar.ti.howest.be/api/project_badges/measure?project=2022.project-ii:mars-server-11&metric=vulnerabilities)
![code_smells](https://sonar.ti.howest.be/api/project_badges/measure?project=2022.project-ii:mars-server-11&metric=code_smells)
![bugs](https://sonar.ti.howest.be/api/project_badges/measure?project=2022.project-ii:mars-server-11&metric=bugs)

![duplicated_lines_density](https://sonar.ti.howest.be/api/project_badges/measure?project=2022.project-ii:mars-server-11&metric=duplicated_lines_density)
![coverage](https://sonar.ti.howest.be/api/project_badges/measure?project=2022.project-ii:mars-server-11&metric=coverage)

## What is Salus Security?
Salus Security is a company that focuses on the security of Mars-citizens. With our application we want to help the community on Mars keep themselves but more <b>importantly</b> eachother safe in a world without law-enforcements.

## ![info](./images/info-img-32.png) Quick start (server side) 
1. <b>First of all</b> you need clone the server repository
from the gitlab or using the following `command` in 'cmd/git BASH' in your preffered folder. 
    - > git clone https://git.ti.howest.be/TI/2022-2023/s3/analysis-and-development-project/projects/group-11/server.git 


2. prerequirements that are needed before going in to the code.
    - any kind of text-editor (Visual Studio Code, IntelliJ,...)
    - terminal installs
        - Java: openjdk version 11.0.17 (latest)
        - npm: version 8.19.2 
        - sass: version 1.56.1 
        - node: version 18.12.1
    - ...

*_NOTE:_* make sure you have these versions installed before continuing.

3. From here on out, you can explore application.


## ![info](./images/info-img-32.png) Quick start (client side) 
1. <b>First of all</b> clone the client repository
from gitlab or by using the following `command` in 'cmd/git BASH' within your preffered folder. 
    - > git clone https://git.ti.howest.be/TI/2022-2023/s3/analysis-and-development-project/projects/group-11/client.git 

2. <b>Then</b> you open the folder in VS code and go to the index.html file. On this file you Right-mouse-click and open the file with live-server. 

(you won't have this option unless you have the live-server extention installed. [VS Marketplace Link](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) or in extensions by searching for `Live Server`)

3. From here on out, you can use the application.

**_NOTE:_** for flagging incidents you need to have your location enabled.


## Features
this is a list of every feature in the application.
![homepage](./images/homepage.png)

- Available for all users
    - Flag incident
        - Notification gets send out (for others to assist).
        - A recording will be made of the incident
        - AI will label and validate the crime.
    - View live notifications of reported incincents.
        - The user can get the route towards the incident to assist with the report or help the citizen in danger.
    - A settings page to personalize your notifications and purchase Premium plan.

- Premium Features
    - History
        - Two lists of incident records:
            - incidents you have reported.
            - incidents you have helped reporting.
    - Map
        - A map of incident records with narrow-down options and navigation.
    - Statistics
        - Statistics and Analytics about the reported incidents we have recieved from our users.
        ![charts-preview](./images/charts-img.png)
    - change the notification range on the homepage


## API Specs
Our API documentation can by found [here](https://git.ti.howest.be/TI/2022-2023/s3/analysis-and-development-project/projects/group-11/documentation/-/blob/main/api-spec/openapi-mars.yaml ).


## Support
If you have any questions or are interested in becoming a partner/employee , makes sure to [contact us](https://sites.google.com/student.howest.be/mars-group11/hr/contact-us?authuser=1).

## Marketing Website
Feel free to take a look at our Marketing Website on our [website](https://sites.google.com/student.howest.be/mars-group11/homepage?authuser=1).

## Credits
- <a target="_blank" href="https://icons8.com/icon/VQOfeAx5KWTK/info">Info</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>