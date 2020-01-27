Flickr Clone
Created by Lara Bjork and Bryon Burke on January 23, 2020
Project Description: An app that lets users upload their photos to share with the world. Feel free to clone Flickr exactly or make a variation for a specific audience.

Photo sharing features to include:

    Users create accounts
    Users can add, edit, delete images (but only their own)
    Users can add, edit, delete tags for all images
    Users can tag each other in images (to start simple, you may choose to display a list of all the users in a drop-down menu when you add a tag)
    Users have a profile page (users#show) with a list of all the photos they are tagged in
    Users can "favorite" images; include image favorites on profile page
    Users can add, edit, delete comments to images

Specifications

The assignment description provided the following specifications:

* Database: The site should have functionality to review products so your database should include a one-to-many relationship between Products and Reviews. All products must have a name, cost and country_of_origin. All reviews should have an author, content_body and rating. (A rating can be a number between 1 and 5.) You can include other fields of your choosing as well.

* Landing Page: The landing page should include basic information about the company and should allow users to easily navigate to other areas of the site. This page should also include the three most recently added products and the product with the most reviews. See more information in the Scopes section below.

* Products: The site needs to include a products section with a list of the tasty products that Mario sells. Each product should be clickable with a detail view. * Users should be able to add, update and delete new products. Don't worry about user authentication. Assume everyone who visits the site is an admin for now. * Users should be able to click an individual product to see its detail page. (You will not be expected to show the product's average rating.) * Users should be able to add a review to a product.

* Scopes: Your site should use scopes to display the following information on the site: * The product with the most reviews. * The three most recently added products. * All products made in the USA for buyers that want to buy local products. NOTE: The assignment asked us to allow people to view locally made products, but none of the data from Faker that I seeded had coffees from the USA (understandably). I used Rwanda instead for this scope.

* Validations: Your site should include validations for the following: * All fields should be filled out, including rating. * Rating can only be an integer between 1 and 5. * The review's content_body must be between 50 and 250 characters.

_* Callbacks: Your site should include a callback for the following: * All products are automatically titleized (first letter of each word capitalized) before they are saved to the database.

* Seeding: Your project should include seed data for 50 products and 250 reviews. Use Faker with a loop to seed the database.

* Flash Messages: The project should include flash success and error messages for creating products and reviews.

* Overall Styling: You'll be demoing this site to the CEO of Mario's Specialty Foods, so it should look presentable.
Technologies Used

Ruby 2.5.1, Rails 6.0, Bundler, PSQL/Postgres Gems added manually after initial project setup: Capybara, jquery-rails, faker, bootstrap-sass, sassc-rails, rspec-rails, launchy, shoulda-matchers Project was written using Google Chrome. No other browsers were tested.
Project Setup instructions

    Ensure that you have the correct versions of Ruby, Rails, and PSQL installed.
    Clone the project locally from github (https://github.com/larabjork/mario-coffee.git).
    Install Bundler if you do not already have it by running gem install bundler in the terminal.
    Run bundle install to manage gems; if you make additional changes to the Gemfile, you will need to run this command again.
    Run rake db:create, which should create two databases: mario_coffee_development and mario_coffee_test.
    Run rake db:migrate, followed by rake db:test:prepare.
    To seed the databases with placeholder information, run rake db:seed, which should give you 50 products and 250 reviews.
    Enter rails s or rails server at the terminal prompt.
    Open a browser window and type localhost:3000 in the address bar.

If something doesn't display correctly or goes wrong somehow, please contact me at lara.m.bjork@gmail.com and I will do my best to troubleshoot for you.
Known Issues and Limitations

    No known bugs.

Where to Find This Project

https://github.com/larabjork/mario-food-emporium.git
License

This software is licensed under the MIT license.

Copyright (c) 2020 Lara Bjork
