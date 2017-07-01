# Benj's EZ Rails Tutorial (Hello World!)

1. Create your Rails project

`rails new {project_name}`

It will build a bunch of stuff.  `cd` into the folder it's made.

2. There are many folders.  Here are the ones that matter.

* app: This has literally everything.  Models, views, and controllers.  Even your Javascript and CSS goes here under Assets.

* config: routes.rb and environment.rb are all you will ever use.  routes.rb will tell Rails which controller should handle which actions.  Most of this is automatic.  environment.rb is where you store environment variables.

* db: Migrations and Schema.  Database stuff.
