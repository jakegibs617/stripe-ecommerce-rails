#  Adding Stripe Payments to your Ruby on Rails Application

For each chapter, any links mentioned or notes will be included below in the appropriate sections.

## 1.1 What we'll be covering

* Stripe - https://stripe.com
* Stripe Subscriptions - https://stripe.com/subscriptions
* Stripe.js - https://stripe.com/docs/custom-form
* Stripe Ruby - https://stripe.com/docs/libraries#ruby-library

## 1.2 Requirements

We're using Ruby 2.3.1 and Rails 5.0.0.1 in this course. If you don't have a recent version of Ruby (2.2+) or Rails (4.2+), you can follow the guides here:

* macOS / OS X - https://gorails.com/setup/osx
* Ubuntu Linux - https://gorails.com/setup/ubuntu
* Windows - http://blog.teamtreehouse.com/installing-rails-5-windows

We're also using Bootstrap v3.3.7 which you can find documentation for at http://getbootstrap.com


## 2.1 Adding products

```
# Generate a new Rails application named store
rails new store

# Create the database model named Product and all the views associated with it
rails g scaffold Product name description:text secret:text

# Remove the default scaffold stylesheet
rm app/assets/styles/scaffolds.scss
```
