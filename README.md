# gemstracker-responsive-template
As of version 1.7.2 this is the default template for GemsTracker. It makes use of bootstrap and is responsive.

## Installation
Just install the template by adding a line to your composer.json.

The template depends on a logo in your project's public dir (normally htdocs) at the location images/logo.png

## Configuration
You can choose between a simple configuration or and advanced configuration. The first one will only let you adjust the most basic settings for the template while the latter will let you configure almost everything yourself.

<describe how to>

## Available placeholders
The template hase several placeholders you can render information to. The image below shows all possible positions and their names.

<image>

### Example project.ini
```ini
layoutPrepare.title                 = 1
layoutPrepare.projectName           = header
layoutPrepare.login                 = login_status
layoutPrepare.contact               = 0
layoutPrepare.localeSet             = language
layoutPrepare.organizationSwitcher  = organization
layoutPrepare.version               = footer
layoutPrepare.user                  = 0
layoutPrepare.time                  = 0
layoutPrepare.menuActiveBranch      = 0
layoutPrepare.menuHtml              = 1
layoutPrepare.menuTopLevel          = 0
layoutPrepare.navigation            = 0
layoutPrepare.crumbs                = main
layoutPrepare.messages              = main
layoutPrepare.css                   = 1
layoutPrepare.favicon               = 1
layoutPrepare.dojo                  = 0
layoutPrepare.jQuery                = 1
```