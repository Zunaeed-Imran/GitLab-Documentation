# GitLab-Documentation
i will make document how i should added code in GitLab.

#### to create new branch.
- `git checkout -b 182-admin-solve-refreshing-to-show-customer-approve-list`
- and with tha ticket number and use "-" and all text should be lowercase.

#### some time later we should pull form develop branch.
- `git pull origin develop`
- to not facing any error.

### For Migrateing when sometimes need.
- `make shell`
- `php artisan migrate`
- exit from shell
- `make seed`

### Before MR.
- branch name set
- added command.
- `make shell` in terminal to enter.
- `npm run format`
- `npm run lint`
- `npm run build`
- for API
- out side the shell to run build.
- `docker compose build`
- to check branch name `git status`
- before give merge request check the source should be develop.
- after create MR added some command in the lark.
- Added comments
- Resolved comments. 
- Could you please review it again?
- Resolved comments in.
- Reviewed and approved.
- Added query
- Reviewed and approved API MR 120
- Reviewed and approved UI MR 243. Here, 192 is issue ID.
- 1051-resolve-comments

### More command before merge FOR ui.
- `docker compose run --rm real-estate-ui npm run lint`
- `docker compose run --rm real-estate-ui npm run format`
- `docker compose run --rm real-estate-ui npm run build`

### Delete branch from local PC after MR the branch.
- to delete from local `ctrl+shift+p`
- write `delete git branch`
- and select `Git Delete Branch...`
- than select the brahch i wan't to delete.
- than select delete, than it will delete the remote branch.

### If wan't to to pull develop Even not commiting from current branch.
- `git config pull.rebase false`
- than pull from develop
- than change synchronize change click.

### REALESTATE PROJECT SEED AUTO ADMIN PASSWORD.
- Username: `user@example.com`
- Password: `p@sSw0rd`
- userid: `01j5153eh6m6z13kht7w5e2xd8`
- contactNumber: `+8801000000000`


### Some debuging command.
- to check error in terminal in docker larevel project.
- `make laravel-logs`
- to check storage error in terminal.
- `less +G storage/logs/laravel.log`
- to quite the terminal
- `q`

### Some mroe docker comment.
- `docker network ls` to see network list.
- `docker composer stop` to stop docker compose.
- `docker ps` 
- `docker container stop ***all containerNametoStop`

### Data set in school_id table in database
- `UPDATE users 
SET school_id = '01jq38nwbs78f45r0gym9pbt4d';`