# SilverStripe Weblog Module

SilverStripe Weblog is a basic blogging framework. The core package doesn't contain complicated
permissions, authors, comments, tags or categories. These features can be added separately
if necessary & when needed through extensions such as
[weblog-categories](https://github.com/axllent/silverstripe-weblog-categories).

The SilverStripe Weblog module was built from the ground up, however is based on the SilverStripe Blog
[module](https://github.com/silverstripe/silverstripe-blog), and borrows some ideas and methods
from the project.


## Features

- Basic foundation for Blog and BlogPosts
- A single custom "Weblog" permissions group `CMS_ACCESS_Weblog`
- Scheduled blog posts
- Featured image for blog posts
- Integrated with `silverstripe/lumberjack` for easy post management
- Blog RSS
- Open Graph meta tags


## Documentation

- [Installation](docs/en/Installation.md)
- [Configuration](docs/en/Configuration.md)


## Requirements

```
silverstripe/cms: ^4.0
silverstripe/lumberjack
```


## Suggested Modules

- [axllent/silverstripe-weblog-categories](https://github.com/axllent/silverstripe-weblog-categories) - Blog categories module
- [axllent/silverstripe-weblog-wp-import](https://github.com/axllent/silverstripe-weblog-wp-import) - A tool to import WordPress blog posts
