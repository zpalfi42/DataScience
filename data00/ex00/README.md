First step:
Install postgresql postgresql-client

Second step:
Enter postgres with command 'sudo -u postrges psql'

Third step:
Create user zpalfi with: "CREATE USER zpalfi WITH PASSWORD 'mysecretpassword';"

Fourth step:
Create database with: "CREATE DATABASE piscineds WITH OWNER = zpalfi;"

Fifth step:
Connect to database with: "psql -U zpalfi -d piscineds -h localhost -W" and prompting the password 'mysecretpassword'