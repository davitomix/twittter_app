# Twitter Clone App

A simple Twitter Clone App.
The app itself will feature a basic CRUD principle where we can create, read, update, and destroy Tweets.
On top of the Tweets, I use a  gem called Devise which makes creating an entire user role and authentication system easy. Combined with this gem we can authenticate users who want to author Tweets. A user's Tweets are then also tied to their account. The end result is a public facing site with a stream of tweets from different users. Users that have and account can login to create their own Tweets to add to the public stream.

## Built With

- Ruby,
- Ruby on Rails,
- Html, CSS and JS
- Ruby lint Rubocop.

## Getting Started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

## Authors

👤 **David Eli Martinez Garcia**

- Github: [@davitomix](https://github.com/davitomix)
- Linkedin: [linkedin](https://linkedin.com/linkedinhandle)


## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](issues/).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](https://opensource.org/licenses/MIT) licensed.
