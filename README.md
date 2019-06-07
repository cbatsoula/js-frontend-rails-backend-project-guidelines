# Rails API Project

## Setup

Follow the steps here to set up your backend:
https://github.com/learn-co-students/nyc-web-students-042219/blob/master/28-rails-api/README.md

### Backend Requirements

1. Create a Rails API with two models
1. Create serializers for each model with at least one custom method
1. Create the routes and controller actions for `index` and `show` for at least one model, make sure to create instances of your models from `rails console` so you have some sample data to work with
1. **BONUS** Add a `create` action that creates a new instance in your database and returns JSON object for the newly created instance in the response
1. **SUPER BONUS** Add an `update` action that accepts a `PATCH` request and updates some attributes on your model, or a `delete` action

### Frontend

1. Render all instances from one model when the page loads
1. Provide a way for a user to filter or sort by triggering some even on the DOM (entering text in an input field; clicking a 'sort' button; picking a value from a select dropdown)
1. **BONUS** If you added a create action to your backend, add a form to your frontend to allow users to create new instances of your model
1. **SUPER BONUS** Add a way to update some attribute on your backend or delete some instance of a model
