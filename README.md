# Shiny Notes
Notes taking while adventuring up the RoR Path


## General Concepts

### Command Line

#### touch
Designed to update the modification timestamp of a file or directory without otherwise affecting it, but as a side-effect it creates a new blank file if one doesn't already exist. 

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
