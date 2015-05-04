# codedaily-v2

## Getting started

### Step 1: Clone the source code
Clone the source code from Github to your local machine, for example: ~/Code/codedaily-v2

### Step 2: Run bundle install command
Run the following command to setting up the project dependencies 
```
bundle install
```

### Step 3: Setting up database
You must have `mysql` installed on your local machine. 

If your `mysql server` does not have `codedaily_v2` database yet, run the following command to login as `root`:
```
$ mysql -u root -p
``` 
Then run this query to create the database:
```
CREATE DATABASE codedaily_v2
```

### Step 4: Run the web server
When everything is ok, run the following command to start server:
```
rails s
```

Happy coding ^^
