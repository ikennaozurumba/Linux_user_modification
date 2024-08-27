# User Modifications in Linux

## This file list linux commands to add and mpdifiy users and groups as well as pictures showing execution of these commands

### 1. Create a group with the following options:
- groupname: work
- gid: 1010

![create_group_work](./images/create_group_work.png)

### 2. Create a user with the following options:
- username: samson
- home: /home/samson
- shell: /bin/sh
- user ID: 1005
- group: work
- gecos (fullname, room number, work phone, home phone): "Samson Bryan,36,123-456-789, 456-789-101"

![create_user_samson](./images/create_user_samson.png)

![Details_user_samson](./images/samson_details.png)

### 3. Change user 'samson' login shell to /bin/bash

![change_login_shell](./images/change_login_shell1.png)


### 4. Create another user with the following options:
- username: peter
- gid: 1010
- no home directory
- disable password
- gecos (fullname, room number, work phone, home phone): "Peter Kyle,37,234-678-989,,"

![create_user_peter](./images/create_user_peter.png)
  
![Details_user_peter](./images/peter_details.png)


### 5. Create group with the following options:
- groupname: finance
- gid: 1011

![create_group_finance](./images/create_group_finance.png)

### 6. Create another user with the following options:
- username: john
- group: finance
- disable login
- gecos (fullname, room number, work phone, home phone): "John Doe,38,345-678-989,,"

![create_user_john](./images/johns_details.png)

### 7. Create a user with the following options:
- username: paul
- gid: 1010
- encrypt home directory

![create_user_john](./images/create_user_paul.png)

### 8. Add users samson & paul to the finance group

![add_users_to_finance](./images/add_to_finance.png)


### 9. Create group 'marketing', add paul to marketing, delete group marketing

![add_&_del_users](./images/add_to_marketing.png)


### 10. Prompt paul to change his password
- add an expiry date to paul's account
- edit the maximum number of days between paul's password change to 5
- add a warning for paul to change his password from day 4


![edit_paul_account](./images/add_to_paul.png)

### 11. Enable members of work group to only run cat on /etc

![edit_sudo](./images/edit_sudo_.png)
