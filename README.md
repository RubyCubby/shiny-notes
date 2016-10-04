# Shiny Notes
Notes taking while adventuring up the RoR Path


## General Concepts

### Command Line

#### touch
Designed to update the modification timestamp of a file or directory without otherwise affecting it, but as a side-effect it creates a new blank file if one doesn't already exist.

### Speaking Ruby

#### erb

ERb, embedded Ruby. Primary template system for including dynamic content in web pages.

### Templating

```ruby
  <% ... %>
```
Exectutes the code inside.

```ruby
  <%= ... %>
```
Exectures and inserts the result into the template.

### Testing

#### Red, Green, Factor cycle
Many testing tools represent failing tests with the color red and passing tests with the color green.

```ruby
  get 'static_pages/about'
```

creates a helper called 

```ruby
  static_pages_about_url
```
