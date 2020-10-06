# README

Modeling  demo users
  
    id : integer
    name : string
    email : string

Modeling  demo microposts
    
     id : integer
     content : string
     user_id : integer

Users resources
     
      1 -used scaffold to generate users resources
      rails generate scaffold User name: string email:string
      2- Rake db:migrate

     Microposts resources
     1-used scaffold to generate users resources
      rails generate scaffold Micropost name: string email:string
      2- Rake db:migrate


Users has_many Micropost


  Put micro in Micropost
  validates :content, lenght: {maximun: 140}    






This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
