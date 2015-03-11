# A Static Site Built with Proteus

## About Proteus
[Proteus](http://github.com/thoughtbot/proteus) is a collection of useful
starter kits to help you prototype faster. It follows the
[thoughtbot styleguide](https://github.com/thoughtbot/guides) and includes our
favorite front end tools.

Getting Started
---------------
Set up your project in your code directory
```
git clone git@github.com:thoughtbot/proteus-gulp.git your-project-folder
cd your-project-folder
git remote rm origin
git remote add origin your-repo-url
```

Install the dependencies
```
npm install
```

Run the server
```
gulp
```

Deploy to Github Pages
```
gulp deploy
```

Or install the [Proteus gem](https://github.com/thoughtbot/proteus) and enjoy some shortcuts.

Stylesheets, images, fonts, and javascript files go in the `/source/assets/` directory.
Vendor stylesheets and javascripts should go in each of their `/vendor/` directories.
The source folders for images and fonts have a `.keep` file in them so they can be in the repo, but you can remove those files.

Credits
-------
Proteus is maintained and funded by [thoughtbot, inc](http://thoughtbot.com/community)

Thank you to all [the contributors](https://github.com/thoughtbot/proteus-middleman/contributors)!

License
-------

The names and logos for thoughtbot are trademarks of thoughtbot, inc.

Proteus Gulp is Copyright © 2014 thoughtbot, inc. It is free software, and may be redistributed under the terms specified in the LICENSE file.
