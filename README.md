Below are the steps to run Ruby on Rails applications on your system.

Install the prerequisites:

```
Node.js
Yarn
```

Make sure Ruby is installed on your system. Start a terminal and run command:

```ruby -v```
Make sure Ruby is installed (version 2.7.2 is recommended for this application).

```rails -v```
If you see a Rails version 6+ then you are good to start, otherwise you must setup Ruby on Rails.

Once you've cloned this respository

Make sure you have ```bundler``` installed, and then navigate to the application root directory and install the dependencies with:

```bundle install```

Now create the database and migrate schema with

```rake db:create```

```rake db:migrate```

Now you can run your application

```rails s```
