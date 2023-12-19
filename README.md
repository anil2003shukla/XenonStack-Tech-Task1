
Important
Backend is in the server folder.
First create the categories e.g. web dev, Python, etc. (without categories courses cannot be added). To create categories create an Admin account and go to dashboard then admin panel.
To create an Admin account first sign up with a student or instructor account then go to your Database under the users model and change that 'accountType' to 'Admin'.
Installation
Clone the repository to your local machine.

Install the required packages.

cd Study-Notion-master
npm install

cd server
npm install
Set up the environment variables:

Create a .env file in the root directory. Add the required environment variables, such as database connection details, JWT secret, and any other necessary configurations.

Start the development server.

npm run dev
Open the project in your browser at http://localhost:3000 to view your project.

The project is set up to use postcss-cli to process your CSS files. You can add your own tailwind.config.js file to customize your Tailwind setup.
Installation
git clone https://github.com/himanshu8443/Study-Notion-master.git
Install the required packages.

cd Study-Notion-master
npm install

cd server
npm install
Set up the environment variables:

Create a .env file in the root directory and /server Add the required environment variables, such as database connection details, JWT secret, and any other necessary configurations check .env.example files for more info.

Start the development server.

npm run dev
