# Item Catalog: The Item Catalog 

by Kwamena B-E, for Udacity's Full Stack Nanodegree

### 

This application provides a list of items (Massive Open Online Courses) within many categories (Course providers) and has a user registration and authentication system.  Registered users (anyone with a GitHub account) will have the ability to post, edit and delete their own items.


### How to run

This simple web application uses GitHub for authorization and authentication.  To simulate security best practices, the API keys are not in the main application file or hard-coded.  However, to facilitate grading, a shell script, `export_keys.sh`, is available to export API keys (current as of the time of submission) to server environment variables.


This repository contains the `mooc-catalog` submodule, provisioned as `catalog`. 


To load this website up:


1. Download or clone the `p3/vagrant` directory.

2. Initialize the Vagrant vm via `vagrant up`, which should set up on `localhost:5000`.

3. Connect to the virtual machine: `vagrant ssh`.

