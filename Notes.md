
Requires npm.

# Install Angular
https://angular.io/guide/setup-local

> npm install -g @angular/cli

> cd .. \
> ng new angular-crash

To run the application

If on Windows 10, may need to run this before running the application :
> Set-ExecutionPolicy -Scope CurrentUser  RemoteSigned

Then :
> ng serve

# Create components

> ng generate component components/header

> ng generate component components/button

> ng generate component components/tasks

> ng generate component components/task-item

# Add icons

ng add @fortawesome/angular-fontawesome@<version>
We take the latest
> ng add @fortawesome/angular-fontawesome
Choose Free Solid Icons, Free Regular Icons and Free Brands Icons the click enter

# Create services

> ng generate service services/task




