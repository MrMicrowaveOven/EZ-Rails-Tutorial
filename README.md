# Benj's EZ Rails Tutorial (Hello World!)

1. Install Rails

Open up a command line prompt. Verify that you have a current version of Ruby installed:

`ruby -v`

It should respond `ruby 2.3.1p112` or something.

Verify that sqlite3 is correctly installed and in your PATH:

`sqlite3 --version`
The program should report its version.  Version doesn't really matter.

To install Rails, use the gem install command provided by RubyGems:

`gem install rails`

To verify that you have everything installed correctly, you should be able to run the following:

`rails --version`

If it says something like "Rails 5.1.0", you are ready to continue.

2. Create your Rails project

`rails new {project_name}`

It will build a bunch of stuff.  `cd` into the folder it's made.

3. There are many folders.  Here are the ones that matter.

* app: This has literally everything.  Models, views, and controllers.  Even your Javascript and CSS goes here under Assets.

* config: routes.rb and environment.rb are all you will ever use.  routes.rb will tell Rails which controller should handle which actions.  Most of this is automatic.  environment.rb is where you store environment variables.

* db: Migrations and Schema.  Database stuff.

4. The first "Hello World!"

On the command line type `rails s`.  This starts the rails server.  Among other things, it should mention `Rails 5.1.2 application starting in development on http://localhost:3000`.  Go to http://localhost:3000 (or whatever it mentiond).

You should see a page that makes you happy.  If not, be sad.
