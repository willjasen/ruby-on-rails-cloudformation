# ruby-on-rails-cloudformation

To make deploying a Ruby on Rails project as easy as possible for non-technical users while also creating a secure environment, this project chose Amazon CloudFormation to document a Ruby on Rails stack from start to finish.

This project assumes that the following gems are used:
- 'figaro', in particular for application.yml as a local repository for environment variables
- 'unicorn', as a threaded web server

There may be issues deploying a particular Rails project using this template, so please fork the project, create changes, and commonly needed fixes will be merged in.
