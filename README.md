# Todo

This single-page to-do application features a fluid user interface that– by using JavaScript– allows users to rapidly add dynamic content.

![todo](/app/assets/images/todo.png)


### Prerequisites

Setting up ruby on rails enviroment

[Getting Started with Rails](https://guides.rubyonrails.org/v5.0/getting_started.html)

### Installing

Once the ruby on rails enviroment has been set up.

Git clone the repository to your local machine:

HTTPS:
```
$ https://github.com/joelpankito/todo.git
```
SSH:
```
$ git@github.com:joelpankito/todo.git

```
Next, cd into the repository you cloned and install the necessary dependencies by running:
* In other to create your local database run:
```
rake db:create
```
```
rake db:migrate
```
* Install the necessary dependencies
```
$ bundle install
```
You will then be able to start the app locally by runnning:
```
$ rails server -b 0.0.0.0 -p 3000
```


## Built With

* [Rails](https://rubyonrails.org/) - web application framework

* [Postgres](https://www.postgresql.org/) - The database engine.

* [Bootstrap](https://getbootstrap.com/) - Bootstrap is a free and open-source CSS framework

* [JQuery](https://jquery.com/) - jQuery is a JavaScript library 

* [Devise](https://github.com/heartcombo/devise) - flexible User authentication 

* [Simple_form](https://github.com/heartcombo/simple_form) - building forms

* [FactoryGirl](https://github.com/thoughtbot/factory_bot) - test robot

* [Rspec](https://github.com/rspec/rspec-rails) - test enviroment

## Authors

* **Joel Pankito** - *Complete work* - [Todo](https://github.com/joelpankito)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
