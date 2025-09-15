Content:

# Task 1: Strapi Setup

This repository contains the setup for Task 1: creating a Strapi project, running it locally, exploring the folder structure, creating a sample content type, and pushing it to GitHub.

## Project Setup

### 1. Clone the Repository
```bash
git clone https://github.com/mrsid743/task-1-strapi-setup.git
cd task-1-strapi-setup

2. Install Dependencies

Ensure you have Node.js (v18 or v20) installed.

npm install


If you encounter dependency errors, use:

npm install --legacy-peer-deps

3. Start the Strapi Server
npm run develop


The server will start at http://localhost:1337
.

4. Access Admin Panel

Open http://localhost:1337/admin

Create an admin user to access the dashboard.

Create a Sample Content Type

Go to Content-Types Builder in the Admin Panel.

Click Create new collection type and name it Article.

Add fields such as:

Title (Text)

Content (Rich Text)

Click Save.

Add sample entries in Content Manager → Articles → Add New Article.

Folder Structure
my-strapi-app/
├── api/
├── config/
├── extensions/
├── node_modules/
├── public/
├── src/
├── package.json
├── package-lock.json
└── README.md


api/ → your content types and APIs

config/ → project configuration

extensions/ → custom Strapi extensions

public/ → static files

src/ → source code

node_modules/ → dependencies

README.md → project documentation

Push Changes to GitHub
git add .
git commit -m "Initial Strapi setup"
git push -u origin main

Loom Video

[https://www.loom.com/share/253c4d2df87c4848b84a6a33fa0c87c5?sid=b1c5d37c-ea41-416a-a582-f9921a24464f]
