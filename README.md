# Introduction

This project can be done thanks to [Mackenzie Child](https://www.youtube.com/watch?v=abcnfFS_DS8) YouTube tutorial. There are some slight change in this project from the YouTube tutorial. This project use Ruby 2.6.3, Rails 5.2.3 and using active storage as image attachment instead of paperclip. 

## Run this project locally

_This tutorial assumes you have Ruby 2.6.3 installed. If not, please [install it using RVM](https://rvm.io)._

1. Clone this repository to your local machine.

```bash
git clone git@github.com:helmihidzir/pin_board.git
```

2. Change into the `pin_board` directory.

```bash
cd pin_board
```

3. Install the project dependencies using bundler.

```bash
gem install bundler
bundle install
```

4. Create the SQLite database.

```bash
rails db:create
```

5. Run the database migrations.

```bash
rails db:migrate
```

6. Start the Rails server.

```bash
rails s
```

7. Lastly, navigate to <http://0.0.0.0:3000> to play around with the project.
