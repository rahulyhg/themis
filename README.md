# themis | A minimalistic and responsive Kirby CMS theme for photographers
themis is an open source theme for [Kirby CMS](http://getkirby.com). It is responsive, free and you can use it out of the box. Test the live demo [here](http://themis.niklausgerber.com).

## Features
- Clean PHP, HTML, jQuery and CSS theme for Kirby CMS
- Responsive
- Works on any modern web browser
- Prepared for SEO
- Beautiful typography designed for perfect readability on any device
- Non cluttered minimal design for presenting your best photos
- Automatically generates thumbnails for the overview site
- Can be set up to your needs in less then 10 minutes
- Oh and it is free

## Kirby CMS
Kirby is a file-based CMS. Easy to setup, easy to use, flexible as hell. You will need to download Kirby and install it on your server. Once you are set you can start with the installation of monochrome. [You are free to use and modify this theme, but you must purchase a Kirby license if you want to use it in production](http://getkirby.com/buy).

## Step one | Installation
[Download the themis theme from GitHub](https://github.com/niklausgerber/themis/zipball/master). Delete the content of those three folders of your Kirby installation.

- /assets
- /content
- /site

Drag the themis theme with all its files to your kirby installation and replace existing files with them. Make sure you also copy the .htaccess files. If you now upload your kirby installation to your server the themis theme should be up and running.

## Step two | Configuration
I will quickly guide you through the different folders and explain you which settings you will have to change and which settings need optional modification.

### /assets/css
The CSS files are all set up for the beautiful themis theme. If you want to change the appearance of the theme you will find all important CSS styles in the base.css.

### /assets/images/icons/header
Replace this image with a 2200 × 480 pixels version of your own. It will be used as the header image on your homepage. The image must have a height of 480 pixels but can be wider than 2200 pixels.

### /assets/images/icons/facebook
Replace this image with a 646 × 1027 pixels version of your own. It will be used if people are sharing content on Facebook and your article does not contain any images.

### /assets/images/icons/facicon.ico
Replace this image with a 16 × 16 pixels version of your own. This favicon will be displayed in the browser bar and the bookmark collection of your visitors.

### /assets/images/iOS
Replace these two image with a 72 × 72 pixels and a 114 × 114 pixels version of your own. This icon will displayed if an iOS user is adding your website to the home screen.

### /assets/js
Nothing to do here. jquery-1.7.1.min.js helps to power the theme, jquery.backstretch.min.js resizes the background images on the detail page and jquery.wookmark.js will handle the image containers on your homepage. If you have more JavaScripts you should add them here.
 
### /content/.htaccess
Make sure you copy the .htaccess file. It will make sure no one can snoop your content folders.

### /content/01-articles
Contains your photos. I added some examples to give you a head start. For each photo article you must fill the details in the article.txt and give at least one tag. Please make sure that your tags have no spaces inside a tag. You can multiple comma separated tags (Tag1, Tag2, Tag3 etc.). Also you must upload your photo. I suggest that the images should be at least 1024 × 768 pixels. You can upload JPEG, GIF or PNG.

### /content/home
Your error page. Please update the description according to your site.txt file.

### /content/error
Your error page. Please update the description according to your site.txt file.

### /content/feed
Settings for the RSS feed.

### /content/site.txt
Overall site settings.

### /content/sitemap
Generates an Google friendly XML site map. You can add the URL afterwards into the robots.txt.

	User-Agent: *
	Allow: /
	Sitemap: http://yourdomain.com

### /site/snippets/footer.php
The complete footer of your page. Please change it at will but I am happy if you leave the comment on the last line.

### /site/snippets/footer-article.php
Didn't want to load the same scripts so I made a separate snippet. Please change it at will but I am happy if you leave the comment on the last line.

### /site/snippets/header.php
The complete header of your page. Please change it at will.

### /site/templates/article.php
Style of the photo detail page.

### /site/templates/default.php
Your home page.

### /thumbs
**Contains all the thumbs which are generated by Kirby. Make sure it is writable**

## Disclaimers

### Credits
Please support humans.txt (http://humanstxt.org/). It's an initiative for knowing the people behind a website. It's a TXT file that contains information about the different people who have contributed to building the website.

	themis Theme: https://github.com/niklausgerber/themis
	Niklaus Gerber
	Twitter: @niklausgerber
	URL: http://niklausgerber.com
	Location: Bern, Switzerland
	
If you are happy with themis please link to http://niklausgerber.com & follow me on [Twitter](http://twitter.com/niklausgerber).

### Licences
themis by Niklaus Gerber is licensed under a Creative Commons Attribution-ShareAlike 3.0 Unported License.
Based on a work at github.com.

### Download, Fork, Commit.
If you think you can make this better, please Download, Fork, & Commit. I'd love to see your ideas.