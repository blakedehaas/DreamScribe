<h1>DreamScribe</h1>

<p>Dreamscribe is a smart journaling app that utilizes ChatGPT to help users enhance their mindfulness and improve their journaling experience. With the goal of making journaling more accessible and efficient, Dreamscribe streamlines the process of revisiting journal entries, while also providing valuable insights into users' moods and emotions. Users can create customized journals complete with a cover theme of their choice. They are then able to write notes freely, without worrying about grammar or formatting. Once a note is written, users can choose to format the note, which corrects any errors and formats the content for readability. The summarize function enables users to get an overview of an entry without having to read through it in its entirety. Dreamscribe also has smart mood analysis for notes. By enabling automatic mood analysis for a journal, users can gain a deeper understanding of their emotional states and observe their mood patterns over time. Dreamscribe is a game-changing app that makes journaling more efficient and effective for users by leveraging the power of artificial intelligence. With its advanced features and user-friendly interface, Dreamscribe is the perfect tool for anyone who wants to enhance their mindfulness and improve their mental well-being.

<h2>Developer Lead</h2>
<p>
Blake DeHaas<br>
</p>

<h2>Design Lead</h2>
<p>
Reece Cogswell<br>
</p>

<h2> How To Run Dreamscribe </h2>
<h3> Add your OpenAI API key to the .env </h3>
<p> Edit the .env file within the 'All Project Code and Components' that contains the following lines:</p>

\# database credentials \
POSTGRES_USER="postgres"\
POSTGRES_PASSWORD="pwd"\
POSTGRES_DB="users_db"

\# Node vars\
SESSION_SECRET="super duper secret!"\
OPENAI_API_KEY="Replace with your OpenAI API Key"
</p>

<p> Replace the OPENAI_API_KEY with your OpenAI API key. You can create a key by going to https://openai.com/blog/openai-api. </p>

<h3> Download Docker Desktop <h3>
<p>Our application uses Docker containers to function.
You can download docker from their website: https://www.docker.com/products/docker-desktop/
</p>

<h3> Launch Docker Desktop <h3>
<p>To run the application locally, you must launch Docker Desktop every time and leave it running in the background.
Then, start up a docker container by typing 'docker-compose up' in the terminal after navigating into the 'All Project Code and Components' folder. Then, navigate to 'localhost:3000' in your browser to access the application locally.</p>

<h2> Technology Stack </h2>
<img src="All Project Code and Components/resources/images/tech_stack.png" height="500">

<h2> How to Run Dreamscribe Tests </h2>
<p>To test the application, ensure that in the file 'package.json' within the "scripts" the function "testandrun" is set as follows: 
"testandrun": "npm run prestart && npm run test && npm run start"
This will ensure that the application will run all test cases properly, as well as start up correctly.</p>

<h2> Application Access </h2>
<p>The application can currently only be accessed locally. The application has been deployed to Microsoft Azure cloud service sucessfully for demos in May 2023. The longterm plan is to host the application in the cloud.</p>

<h2> Special Thanks <h2>
<p>
John Danekind<br>
Ryan Garrett<br>
Elia Muncey<br>
Jared Roberts<br>
</p>
