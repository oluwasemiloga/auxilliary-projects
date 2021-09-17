## Shell Scripting
Hello, welcome to my Project4 implementation file. I will share my shell scripting implementation with screen shots and brief notes.

I launched an EC2 instance with t2 micro family on Ubuntu server 20.04

<img width="952" alt="Aux1" src="https://user-images.githubusercontent.com/20802925/133850624-33c210a0-d913-46b3-be5f-565ffe120604.PNG">

I created the onboard.sh script in my Desktop folder. I struggled with the script a bit so I used the one provided in the youtube walkthrough of the project

<img width="947" alt="Aux3" src="https://user-images.githubusercontent.com/20802925/133853261-09a7742f-2f05-43a8-b052-2c21e9928a08.PNG">

I copied the onboard.sh script from my Desktop folder into the home directory of mmy Ubuntu server instance using the scp command

<img width="960" alt="Aux4" src="https://user-images.githubusercontent.com/20802925/133853759-8a710208-c4cf-49e1-a0c6-c6ad758daab0.PNG">

Then I ssh into my EC2 instance and confirm that the onboard.sh script is in my home directory

<img width="947" alt="Aux5" src="https://user-images.githubusercontent.com/20802925/133853914-23b6e343-801e-4a80-9dec-134a3a3cdf21.PNG">

<img width="959" alt="Aux7" src="https://user-images.githubusercontent.com/20802925/133854091-b7d232a7-0d50-4339-b23c-d2121b44d009.PNG">

I then create the shell folder and change directory into the shell folder

<img width="960" alt="Aux8" src="https://user-images.githubusercontent.com/20802925/133854275-7a08f4b1-755c-4940-abb1-185bac5b34b3.PNG">

I move the onboard.sh shell script from my home folder into the shell folder

<img width="960" alt="Aux9" src="https://user-images.githubusercontent.com/20802925/133854486-e7a105e8-ea05-4886-b342-f2569eb7345d.PNG">

I create the names.csv file and add names to the file

<img width="955" alt="Aux10" src="https://user-images.githubusercontent.com/20802925/133854603-6b22accf-b2bc-4d4f-a152-0b67294d92fd.PNG">

<img width="943" alt="Aux11" src="https://user-images.githubusercontent.com/20802925/133854620-0bcc8bff-dd64-4f27-989b-93da43c1788d.PNG">

I change directory into the .ssh folder and create a file for the public key

<img width="960" alt="Aux13" src="https://user-images.githubusercontent.com/20802925/133854804-e746f4eb-57d1-4cef-b6cc-0f6cae93549d.PNG">

I open the file and paste in the public key

<img width="960" alt="Aux14" src="https://user-images.githubusercontent.com/20802925/133854959-d7e919e3-e64c-4681-92b4-fb3223e73a7c.PNG">

<img width="960" alt="Aux15" src="https://user-images.githubusercontent.com/20802925/133854985-4d5c979b-2910-4426-8b7a-8976f7655743.PNG">

I create a file for the private key and paste in the private key

<img width="960" alt="Aux16" src="https://user-images.githubusercontent.com/20802925/133855266-a7439985-8ef7-4847-bff8-ab8954f3b8c5.PNG">

I create the developers group

<img width="960" alt="Aux19" src="https://user-images.githubusercontent.com/20802925/133855474-9f2022e1-78a9-4b2e-8c8d-06ce0111d2db.PNG">

I modify the onboard.sh script permissions to add execute permission to the file

<img width="960" alt="Aux20" src="https://user-images.githubusercontent.com/20802925/133855714-cd18d48f-cbc6-4730-b732-6b973edfd61f.PNG">

I run the onboard.sh script as the ubuntu user and get the Önly admin can onboard a user" message

<img width="960" alt="Aux21" src="https://user-images.githubusercontent.com/20802925/133855878-f3a192ac-2d17-4715-b45a-e833a7de1021.PNG">

I switch to the root user using the sudo command and run the onboard.sh again. The users are successfully created

<img width="960" alt="Aux22" src="https://user-images.githubusercontent.com/20802925/133856035-7f26d6af-3019-4921-aa42-b89eaee67deb.PNG">

I confirm that the users are created by listing out the home directory contents

<img width="960" alt="Aux23" src="https://user-images.githubusercontent.com/20802925/133856166-8b27b7b0-4755-4c9d-91a4-dc053ca6bf26.PNG">

I test a few of the users to ensure that they can connect to the server

<img width="960" alt="Aux25" src="https://user-images.githubusercontent.com/20802925/133856927-cbd04947-3f3c-4fbc-a256-48ec823b4e8e.PNG">

<img width="960" alt="Aux26" src="https://user-images.githubusercontent.com/20802925/133856956-d805030f-12ce-4819-9528-e9785657e26e.PNG">

<img width="960" alt="Aux27" src="https://user-images.githubusercontent.com/20802925/133856970-378c662e-1846-49de-85e4-daf3c6f5c170.PNG">

<img width="960" alt="Aux28" src="https://user-images.githubusercontent.com/20802925/133856992-6512b916-de83-4fef-a4d9-b633868a16d1.PNG">

Project complete. Thank you.
