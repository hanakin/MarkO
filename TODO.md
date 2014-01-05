TODO.md

# DB
* need some sort of flat db and helper functionality

# Social - extened by each service
* share:link->service
    - returns link for specified service
    - checks if already has share count and updates db
* update
    - updates count in db on click
    - compares db with live count 

# Post
* add
    - strips header info from uploaded markdown file and populates flat database
    - store original version in safe unaccessable from front end location
    - create render version without header info
* single + accepts post_name
    - renders single post page
    - creates cached version
* get + accepts limit and pointer
    - gets list of posts from DB

- upload markdown post files and accompaning images
    + needs to parse out variables inot seperate flat DB (Yaml,REDIS, MongoDB?)
    + save cached html version of file
    + save original file
    + save version minus variables

- generate list of posts based on directory
    + needs to establish proper routing
    + need to septup proper paging
    + need to be able to retrive only sinlge file

# Auth
