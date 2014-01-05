# My ip

The point with this application is just to show your current IP address.

## Installation

Clone the repo and cd into applications root directory:
```bash
git clone git@github.com:alex-ross/myip.git myip
cd myip/
```

Install dependencies by running `bundle install` from the terminal.
Now you can fire of `bundle exec rackup` from the terminal to start the server.

When you visit [localhost:9292](localhost:9292)\* you should see your remote IP
address according to the server. So if your server is localhost and you visit
the app from localhost you probably will se "127.0.0.1"

`*` The domain may be different depending on your rack setup.
