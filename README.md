**Future Ready Talent Projects**

**Project Title:**   Student Personal Portfolio Website


**Project Members** :- Sushant Prasad, Chandani Yadav and Khushi Saroj

**Contrubtions of members**:- -Sushant Prasad Created the web app by using the following language, HTML, CSS and JS.

Sushant Prasad, Chandani Yadav and Khushi Saroj deployed the project in azure by using it's service that is app service, applications insights and language studio in that we created a chat bot.



**Project Description :**

A personal portfolio is a curated collection of your work, accomplishments, skills, and experiences that showcases your expertise and talents to potential employers, clients, or collaborators. It serves as a comprehensive representation of your professional identity and capabilities. Here's a breakdown of what a personal portfolio typically includes, Introduction, resume or CV, Portfolio Projects, Skills and Expertise, Testimonials or Recommendations, Contact Information, etc. When creating your personal portfolio, focus on presenting your work in a visually appealing and professional manner. Finally, don't forget to proofread carefully to ensure accuracy and professionalism.

**Industry Type :**  Lifestyle

**Core Azure Services :**

- **Azure App Service (for hosting the website)**
- **Azure App Insights (to understand the performance and usage of your live web application)**

**Azure AI Services :**

- **Azure Language Services** 
- **Azure Bot Services**

**Web Technologies Used :** 

- **Html**
- **CSS, JavaScript**

**IDE Used :**

- **Visual Studio Code**

**Steps Followed While Deploying :**

1. Built the whole Web Application on the Visual Studio Code.
1. Then Uploaded my WebApp in my GitHub Repository
1. Then Created an Azure APP Service without any code in it.
1. Then Went inside the Created Azure App Service and then to Deployment Center option in Deployment Section of Azure App.
1. Then Selecting the Source as external Source and then pasting the link of my Github repository and Save and sync.
1. Now the Web Application is Successfully Deployed. Click on the Browse option to redirect to our website.
1. Now create the Azure app insights in the same resource group.

**Working Links of Project:**

- **Working Project url**: http://studentpersonalportfolio.azurewebsites.net
  
- **Project Video url**: https://drive.google.com/file/d/1M14dO58rrMv57H72Daua0vfzGkb9WNyL/view?usp=sharing

- **Project Documentation url**: https://drive.google.com/file/d/1CSRuAhpX8czku6abyAaBWOL2K6iX5Cr1/view?usp=sharing

**ScreenShots of the project :**

Go to app service-> create a web app-> create resource group-> enter name-> select runtime stack
![Screenshot 2024-02-26 131015](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/4e228235-bebd-4b85-b9d6-dad757ce7cc6)

select windows plan -> pricing plan -> review + create
![Screenshot 2024-02-26 131144](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/6ebf0644-b38b-43a4-a6fd-48243ea6e36f)

![Screenshot 2024-02-26 131516](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/5afb50c7-82a1-49b1-b893-b32b0d816248)

click on deployment center-> select source(external git)-> (copy the repository from the github and paste it) in Repository-> Branch(main)-> click on save
![Screenshot 2024-02-26 131642](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/0bc0f5d0-8d64-45b0-9871-5ca8bb45366c)

This is our second service that is application insights
![Screenshot 2024-02-26 132204](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/f0ff5118-ac94-4640-96b8-3f9c02d143db)

To connect application insights to the app services go to the app service-> API management-> click on create new
![Screenshot 2024-02-26 132335](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/88bef1b0-3de7-4d9e-ae3b-144e850b6ae2)

Enter the organization name and administrator email
![Screenshot 2024-02-26 132558](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/46196fe0-09ad-4c25-967c-274e8638d4a6)

Go to monitoring select the application insights and click in review + create
![Screenshot 2024-02-26 153030](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/c1c58559-ad42-48ba-9327-d5147627181c)

Now click on Link API
![Screenshot 2024-02-26 153305](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/d2a7cbcc-aa08-4334-b735-2f8599ba9dbd)

Select the App service
![Screenshot 2024-02-26 153343](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/9dd0d83e-ded4-4207-927b-a0761b419261)

Select the app service and click on create
![Screenshot 2024-02-26 153458](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/2162c886-5044-4a22-b3e5-299052916fab)

Our third service is AI service, Go to AI service-> Language service-> Click on create--> select custom question answering
![Screenshot 2024-02-28 142424](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/fb0a8f5b-a4c3-498b-b63f-f7811eeca969)

Select resource group and enter the name
![Screenshot 2024-02-28 142905](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/032bf2b6-cf72-4f2d-84f7-2d20ff5a2110)

Tick the last option and click on review + create.
![Screenshot 2024-02-28 143029](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/516562a3-b5cd-4ed9-b7b0-f7e34e911190)

click on get started with language studio
![Screenshot 2024-02-28 143441](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/39c29902-5275-44e9-908b-3b54228fac0d)

Fill all the details properly, select the resource group and click on done
![Screenshot 2024-02-28 143658](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/9ed5c9d0-c053-4699-9de8-ee66e41d19b1)

click on add source--> select file
![Screenshot 2024-02-28 144434](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/3154e535-0490-47dc-9216-6a50b212d9c6)

upload your question and answer file and click on add all
![Screenshot 2024-02-28 144540](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/af843423-3229-4db4-96b1-146b006eb629)

now click on deploy
![Screenshot 2024-02-28 144656](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/a9d8efa3-e6a1-4055-815b-8529c3701500)

click on create bot
![Screenshot 2024-02-28 144800](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/adc61f21-eef6-4f70-8131-4571e8aa158d)

Select resource group-> bot handle
![Screenshot 2024-02-28 145107](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/94acd97b-fb1c-455c-814c-f4fd45a45a14)

Fill all the details properly and click on review + create.
![Screenshot 2024-02-28 150153](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/a039d8d3-41bc-4111-98ee-2188a8e921c8)

to add chatbot in your html page select web chat
![Screenshot 2024-02-28 151313](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/1c08716b-71f4-4d85-9387-26f90e8a6c77)

copy the secret key and embedded code then paste it into your code
![Screenshot 2024-02-28 151422](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/75b655f0-22dd-4a35-8212-aea945b5e23c)


**WEB OVERVIEW**

**ScreenShots of the website after deploying**

![Screenshot 2024-02-28 160829](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/43a244d2-6c5c-4413-98e5-8f7225904dcb)

![Screenshot 2024-02-28 160925](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/4f6dea42-6857-4adb-b3b7-6c0d11510ac6)

![Screenshot 2024-02-28 161009](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/7a5e77ac-e3b8-44f7-a8b9-a8d58ee1297d)

![Screenshot 2024-02-28 161041](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/810eaa0d-afce-4f4d-8f13-7389c62d6905)

![Screenshot 2024-02-28 161052](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/71a9a5c4-17f5-46e2-b5f6-7de3f0594687)

![Screenshot 2024-02-28 161319](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/0e97187e-22de-4ced-afcb-8cb56450e6ce)

![Screenshot 2024-03-02 133142](https://github.com/SushantPrasad13/Student_personal_Portfolio/assets/144934599/1a77b0ed-1584-4854-b428-f71ed23894ff)






