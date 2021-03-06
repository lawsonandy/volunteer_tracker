# Volunteer Tracker
#### *Created By: Andrew Lawson*
#### *Volunteer Tracker with SQL*

* * *

## Description
This is an application for creating community volunteer projects. Users can create, update, and delete projects as they please, and can also add, update, and remove volunteers from a project.
* * *

## Technologies used
* Bootstrap
* Bundler
* Capybara
* Embedded Ruby
* git
* HTML
* PostgreSQL
* Rspec
* Ruby
* Sinatra

* * *
## User Stories

* As a non-profit employee, I want to view, add, update and delete projects.
* As a non-profit employee, I want to view and add volunteers.
* As a non-profit employee, I want to add volunteers to a project.

* * *
## Installation :

#### Clone the project to your computer and open locally:

* Go to ( https://github.com/andyL89/volunteer_tracker ).

*  Navigate to the green 'code' button on the repository webpage.

* Click on the code button to open the menu.

- Copy the HTTPS code by clicking the clipboard icon to the right of the link.

- Within your Bash terminal navigate to your desired location by using cd followed by your desired directory.

```bash
 cd Desktop
```

- Once you have chosen your desired directory use the command:
```bash
git clone https://github.com/andyL89/volunteer_tracker.git
```

<div
  style="
    background-color: #d1ecf1;
    color: grey; padding: 6px;
    font-size: 9px;
    border-radius: 5px;
    border: 1px solid #d4ecf1;
    margin-bottom: 12px"
>
  <span
    style="
      font-size: 12px;
      font-weight: 600;
      color: #0c5460;"
  >
    ⓘ
  </span>
  <span
    style="
      font-size: 12px;
      font-weight: 900;
      color: #0c5460;
      margin-bottom: 24px"
  >
    Note :
  </span>
  If you have any problems make sure your HTTPS code is correct! The example above might not be the most recent HTTPS code!
</div>


* Within the chosen directory, use the command:

``` bash
code .
```

* Download Gem bundler with the command:

``` bash
gem install bundler
```

* Install dependencies with the command:

``` bash
bundle
```

* Setup database with the following commands:

``` bash
createdb volunteer_tracker
```
``` bash
psql volunteer_tracker < database_backup.sql
```
``` bash
createdb -T volunteer_tracker volunteer_tracker_test
```

* Run tests with the command:

``` bash
rspec
```

* View the site with the command:

``` bash
ruby app.rb
```

* Then, in your browser, navigate to `localhost:4567`

## Addition comments:
* Created on 3/12/21

* * *

## License:
> *&copy; Andrew Lawson 2021*

Licensed under [MIT license](https://mit-license.org/)

* * *

## Contact Information
_Andy Lawson: [Email](alawson89@gmail.com)_