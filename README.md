## Overview 
This is my rails api-only template. 

## Usage 
1. Clone The Repo 
  ```bash
  $> git clone git@github.com:philiplambok/rails-api-template.git your-new-project-name
  ```
2. Run bundle to installing gem in local 
  ```bash
  $> bundle 
  ```
3. Remove the remote 
  ```bash
  $> git remote rm origin 
  ```
4. Remove Logs
  ```bash
  $> rm -rf .git && rm -rf README.md
  $> touch README.md 
  $> git init 
  $> git add .
  $> git commit -m 'initialize'
  ``` 
5. Push Repo 
  ```bash
  $> git remote add origin git@github.com:your_username/your-new-project-name.git
  $> git push origin master  
  ```
6. Done! 

## Gems
- [bcrypt-ruby](https://github.com/codahale/bcrypt-ruby)
- [ruby-jwt](https://github.com/jwt/ruby-jwt)
- [rspec-rails](https://github.com/rspec/rspec-rails)
- [spring-comment-rspec](https://github.com/jonleighton/spring-commands-rspec)
- [factory_bot_rails](https://github.com/thoughtbot/factory_bot_rails)
- [active_model_serializer](https://github.com/rails-api/active_model_serializers)

## Issues 
Have problem when install or something that i don't know? 
Add as the issues in [here](https://github.com/philiplambok/rails-api-template/issues)