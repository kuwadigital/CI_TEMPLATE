CodeIgniter 3 Docker Implementation for Learning Purposes

Step 1: Clone the Repository Clone the repository from GitHub: 
`https://github.com/kuwadigital/CI_TEMPLATE.git`

Step 2: Configure the .env File Complete the .env file with the desired data as needed. (It can be left as default)

Step 3: Build and Run Docker Containers docker-compose up --build This will build the necessary Docker containers, namely: CodeIgniter (3), MySQL, phpMyAdmin.

Step 4: If you need to set special enviroment variables, check the .env file inside the codeigniter folder, that will be mapped in: codeigniter/application/config/database. And the load of the composer vendors are inicialized in the main index.php file in the root folder (codeigniter).

Step 5: Access CodeIgniter 3 and phpMyAdmin Once the previous steps are completed, CodeIgniter 3 should be available at http://localhost:8080 and phpMyAdmin at http://localhost:8081. You can access phpMyAdmin using the credentials defined in the .env file.

That's it! Now you have a lab environment to study, modify, create, break, and recreate a complete code igniter Enhancement System With Multiple Databases.