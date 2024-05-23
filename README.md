
<h5>Create db:</h5> createdb -U postgres monstersdb
<h5>Access db:</h5> psql -U postgres monstersdb
<h5>Create user:</h5> CREATE USER node_user WITH SUPERUSER PASSWORD 'node_password';
<h5>List all users:</h5> SELECT * FROM pg_user
<h5>Echo command:</h5> create output to the terminal

<h5>Change mode  from read and write to executable: Cd bin ->  chmod +x configuredb.sh </h5>
- ls -l 
- npm run configure 
- psql -U node_user monstersdb;

<h5>How to set up password:</h5>
- Open Postgres app, click settings: HBA file -> click show
- Drop the file into the terminal
- Change value ‘trust’ of three first method to md5
- Stop postgres app and start
- npm run configure 
- Enter 3 times for password: node_password

<h5>Website: </h5>Node-postgres.com
<h5>Set up: </h5> index.js => node db