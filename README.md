# I'm feeling :frog:

## Why
Live grading with a custom server because why the hell not.

## Project layout
:frog: :frog: :frog:

### folders
- src (the go stuff)
- handin (the student files)

### How it'll work
1. go server reads the handin folder each time an endpoint is accessed (when it needs to of course)
2. we set up some cron job to run some make command to update the handin files
3. profit

## TODO
1. check endpoint asks for username
2. custom endpoints for each student
3. host on soc or aws
