# Contact Form 7 - Antispam
A trustworthy anti-spam plugin for Contact Form 7 a WordPress, simple but effective!
AntiSpam for Contact Form 7 without boring you with configurations, filters out spam-bots with an auto-learning ai mechanism. 

This is the GitHub repo of the plugin hosted into [WordPress.org Plugin Directory](https://wordpress.org/plugins/cf7-antispam/).

License
-------

This plugin is released under the GNU General Public License Version 2 (GPLv2). For details, see [license.txt](license.txt).


Getting started
---------------

Install the Contact Form 7 plugin through the **Add Plugins** screen (**Plugins > Add New**). After activating the plugin, the **Antispam** sub-menu will appear under the Contact Form 7 menu, in the left sidebar.


Support
-------

Support for this plugin is primarily provided within the volunteer-based WordPress.org support forums. The official website also provides custom development and professional support services.


Contributing to Contact Form 7 - Antispam
-----------------------------------------

You can contribute to the project of AntiSpam for Contact Form 7 collaborating with we to develop this plugin or translating it.

#### Before Start
All ready for development in 2 minutes! In order to setup the development environment, remember to install:
- NodeJS - https://nodejs.org/
- Composer - https://getcomposer.org/

Optionally if you need, you can setup a local environment with wp-env and Docker 
- wp-env (optional) - https://developer.wordpress.org/block-editor/reference-guides/packages/packages-env/
- Docker (optional) - https://www.docker.com/
 
#### if you are downloading the GitHub version, do not forget to install the composer and npm dependencies 
Now place yourself inside the plugins folder of your wordpress installation or if you chose to develop with the local environment in a folder where you keep your projects and type:
```bash
$ git clone https://github.com/erikyo/cf7-antispam.git
$ cd cf7-antispam
$ npm i && composer install
```

#### Easy to contribute! 
If you have choosen to develop with the local environment, run the wp-env command in order to start a local server with WordPress, this CF7-Antispam (this plugin), Flamingo and, of course, Contact Form 7.
```bash
$ wp-env start
```

Special Thanks
--------------

[Tobias Leupold](https://github.com/l3u) - [b8](https://gitlab.com/l3u/b8/) https://nasauber.de/opensource/b8/

[Takayuki Miyoshi](https://github.com/takayukister) - [Contact Form 7](https://wordpress.org/plugins/contact-form-7/), [Flamingo](https://wordpress.org/plugins/flamingo/)  

This project is tested with BrowserStack. [Browserstack](https://www.browserstack.com/)
