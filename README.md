# Budget App

![Microverse](https://img.shields.io/badge/Microverse-blueviolet)

> A mobile web application to manage your budgets

# App Screenshot

![image](https://user-images.githubusercontent.com/75126481/143196248-cbf88eed-c5fc-4b2d-b608-56e874332ec6.png)


We are building a mobile web application where you can manage your budget: you have a list of transactions associated with a category, so that you can see how much money you spent and on what.

## Built With

- Ruby on Rails
- PostgreSQL

## Live Link

[Live Demo](https://hiro-budget-app.herokuapp.com/)

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

- [Ruby](https://www.ruby-lang.org/en/)
- [Rails](https://gorails.com/)

### Setup

- Make sure you have Ruby on Rails set up properly on your computer
- Clone or download this repo on your machine
- Enter project directory

### Install

```sh
bundle install
```

### Database

```sh
# Create user
sudo -u postgres createuser recipe_app -s

# Create the database
rails db:create

## Apply migration
rails db:migrate

# Load the schema
rails db:schema:load
```

### Run

```sh
rails s
```

### Test

```sh
rspec
```

### Troubleshoot

```sh
### Rspec failing
RAILS_ENV=test rake db:reset
```

## Authors

👤 **Aganze Mataba Henri**

- GitHub: [@hiromataba](https://github.com/hiromataba)
- Twitter: [@twitterhandle](https://twitter.com/MatabaHiro)
- LinkedIn: [Hiro Mataba](https://www.linkedin.com/in/hiro-mataba-1bb910209/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Microverse
- Original design idea by Gregoire Vella on [Behance](https://www.behance.net/gregoirevella).

## License

[MIT](./LICENSE)



