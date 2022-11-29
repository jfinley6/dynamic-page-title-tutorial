I talk about how I got this repository setup in my blog post that you can find [here](https://dev.to/jtfinley/dynamic-page-titles-in-ruby-on-rails-4e29).

##### Prerequisites

The setup steps done using the following tools

- Github
- Ruby [2.7.4](https://github.com/organization/project-name/blob/master/.ruby-version#L1)
- Rails [7.0.4](https://github.com/organization/project-name/blob/master/Gemfile#L12)

##### 1. Check out the repository

```bash
git clone git@github.com:jfinley6/dynamic-page-title-tutorial.git
```

##### 2. Create and setup the database

Run the following commands to create and setup the database.

```ruby
bundle exec rake db:create
bundle exec rake db:setup
```

##### 4. Start the Rails server

You can start the rails server using the command given below.

```ruby
bundle exec rails s
```

And now you can visit the site with the URL http://localhost:3000
