# The source code of <https://www.appveyor.com/>

[![Build status](https://ci.appveyor.com/api/projects/status/a8s3e1pd8070x2y9/branch/master?svg=true)](https://ci.appveyor.com/project/AppVeyor-Website/website)
[![dependencies Status](https://david-dm.org/appveyor/website/status.svg)](https://david-dm.org/appveyor/website)


## Getting started

* Install [Node.js](https://nodejs.org/download/)
* Install grunt: `npm install -g grunt-cli`
* Install the Node.js dependencies via npm: `npm install`
* Install Ruby and Ruby DevKit; make sure you select add Ruby to `PATH`, and then run:

    ```shell
    cd C:\RubyDevKit
    ruby dk.rb init
    ruby dk.rb install
    ```

* Run `gem install bundle` and then `bundle install`
* Run `grunt build` to build the static site, `grunt` to build and watch for changes (`http://localhost:4000/`)

## Staging

The `staging` branch is published to <https://appveyor-staging.azurewebsites.net>.

### TODO:

* Fix HTML errors due to duplicate IDs in /updates/

Contributing to the website
---------------------------

**Note:** Major issues or feature requests should be filed on the [issue tracker](https://github.com/mono/website/issues) first, so we can discuss the implications.

If you want to edit a page, the easiest way is to click the ![Edit page on GitHub](https://cloud.githubusercontent.com/assets/1376924/3712375/a6d7bc42-150f-11e4-9ceb-5230cbbfba3f.png) link under the page title on the website.

This will open the source file on GitHub where you can click the pencil button to start editing:
![Arrow to pencil](https://cloud.githubusercontent.com/assets/1376924/3712474/1d2fe57a-1517-11e4-86b2-d083dbeaa4ae.png)

GitHub's editor shows you both the [Markdown](https://guides.github.com/features/mastering-markdown/) source as well as a preview of the rendered page:
![Code editor](https://cloud.githubusercontent.com/assets/1376924/3769433/0f0ca2ee-18e1-11e4-97fc-3493683b853d.png)

After you've finished your changes, enter a proper summary and description and click the "Propose file change" button to open a pull request:
![Propose file change](https://cloud.githubusercontent.com/assets/1376924/3712481/52423448-1517-11e4-8aa8-9c9f9befb6bc.png)
