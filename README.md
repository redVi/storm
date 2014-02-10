storm
=====

Storm &mdash; responsive theme for pelican.

##Configuration Options

Options:

    SITESUBTITLE = 'Description of the site'
    THEME = 'storm'
    CSS_FILE = 'screen.css'
    METADATA = 'Meta description is the home page'

If you want use google search for your site, you may set variable:

    GOOGLE_PARTNER_PUB = 'partner-pub-xxx'

Pages settings:

    #Pages
    DIRECT_TEMPLATES = ('about', 'archives', '404', 'index')
    DISPLAY_PAGES_ON_MENU  = True
    ARCHIVES_URL = 'archives/'
    ARCHIVES_SAVE_AS = 'archives/index.html'
    ABOUT_URL = 'about/'
    ABOUT_SAVE_AS = 'about/index.html'

    MENUITEMS = (('Archive', 'archives/'),
                ('About', 'about/'),)

##Modification

Css-style was written with the help of sass. It means you need install ruby and
sass:

    $ emerge -av ruby
    $ gem install sass compass
    $ cd static
    $ compass compile && rm -rf .sass-cache


##Preview

- Index

![index](https://raw.github.com/redVi/storm/master/index.png)

- Article

![article](https://raw.github.com/redVi/storm/master/article.png)

- About

![about](https://raw.github.com/redVi/storm/master/about.png)


##License

All files that are part of this project are covered by the following license, except where explicitly noted.

[The MIT License](http://opensource.org/licenses/mit-license.php)
