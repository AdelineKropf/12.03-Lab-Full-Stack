# CS208 12.03 Lab - Full Stack - TODO List

- Name: Adeline Kropf
- GitHub: [https://github.com/AdelineKropf/12.03-Lab-Full-Stack/tree/master](https://github.com/AdelineKropf/12.03-Lab-Full-Stack/tree/master)
- Term: Spring 2026

## Project Description

This is my full-stack application for CS208, built with node.js. I modified the 
provided web application for creating a TODO list that allows users to mark a 
task complete and edit a created task. The application uses Express for the 
backend and MariaDB (MySQL) for the database. Please read the following 
instructions carefully because some of the setup only needs to be done once.

## Install the Database

To set up the database, run the `install_db.sh` script in the setup_scripts
directory. This script will install MariaDB and start the server running. You
only need to run this script once per Codespace.

```bash
./setup_scripts/install_db.sh
```

## Create the Database Tables

Create the initial tables by running the following command:

```bash
sudo mysql -u root -p < ./setup_scripts/create_demo_table.sql
```

## Install Dependencies

Install the required dependencies using npm:

```bash
npm install
```

## Run the Application

Start the application using the following command:

```bash
npm start
```

## Access the Application

On Codespaces, you can access the application by forwarding port 3000. Open the
forwarded port in your browser to view the application.