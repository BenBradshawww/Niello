# Niello

Niello is a sleek and sophisticated Hugo dark theme, ideal for highlighting your content in a stylish manner. It comes equipped with essential features like Google Analytics and AdSense support, making it an excellent choice for expanding your online presence.

Note: The master branch is unstable; please use tagged versions for a stable release.

### We are excited to announce the release of version 3.0, featuring significant improvements and new features (2024-09-05). 

Please note that this is a major update and may not be compatible with previous versions. 

An updated version of Hugo is also required. 

We recommend backing up your site before updating.

# Support Features

Dark Mode

Responsive

Multiple Languages - i18n

Content Search

Automatically extract images from an article

Google Adsense

Google Analytics

Tailwind CSS

Syntax Highlight


# Screenshot
![Theme Screenshot](https://raw.githubusercontent.com/guangmean/Niello/master/images/theme_sc_home.png)

# Installation

To install the Niello theme, run the following command in the root directory of your Hugo site:

```shell
git clone https://github.com/guangmean/Niello.git themes/Niello
```

# Configuration

Below is an example of the hugo.toml file for your site (previously known as config.toml):

```toml
defaultContentLanguage = "en"
languageCode = "en-us"
defaultContentLanguageInSubdir = true
baseURL = "https://www.angularcorp.com/" # Must end with splash
languageCode = "en-us"
title = "{CodeTrace} - Discover Issues, Share Solutions."
disqusShortname = "yourDisqusShortname" // Add third-party comments system

staticDir = ["static", "themes/Niello/static"]

theme = "Niello"

[languages]
	[languages.en]
		title = "{CodeTrace} - Discover Issues, Share Solutions."
		languageCode = "en-us"
		LanguageName = "🇺🇸EN"
		contentDir = "content/en"
		weight = 1
		[[languages.en.menus.main]]
			name = 'Home'
			pageRef = '/'
			weight = 1
		[[languages.en.menus.main]]
			name = 'Categories'
			pageRef = '/categories'
			weight = 2
		[[languages.en.menus.main]]
			name = 'Tags'
			pageRef = '/tags'
			weight = 3
		[[languages.en.menus.main]]
			name = 'Contact'
			pageRef = '/contact'
			weight = 4
	[languages.zh]
		title = "{码途轨迹} - 发现问题，分享解决."
        languageCode = "zh-cn"
        LanguageName = "🇨🇳CN"
        contentDir = "content/zh"
        weight = 2
		[[languages.zh.menus.main]]
			name = '首页'
			pageRef = '/'
			weight = 1
		[[languages.zh.menus.main]]
			name = '文章分类'
			pageRef = '/categories'
			weight = 2
		[[languages.zh.menus.main]]
			name = '标签'
			pageRef = '/tags'
			weight = 3
		[[languages.zh.menus.main]]
			name = '联系我们'
			pageRef = '/contact'
			weight = 4
        
[params]
keywords = ""   //SEO keywords
description = ""    //Site description
copyright = "&#xA9; 2019 - 2022 by guangmean. All Rights Reserved."
google_ad_client = "ca-pub-******"  //Optional, replace ca-pub-****** with your content
ga4 = "G-******" //Optional, replace G-****** with your Google Analytics GA4
sharethis = ""  //Optional, Add hou ShareThis appid here
    
```

# Customizing the Theme

If you plan to modify this theme, please note that it is built using TailwindCSS. Before making any changes, you will need to initialize TailwindCSS in your project. Make sure to follow the TailwindCSS setup instructions to properly configure your development environment.

# Google Adsense & Google Analytics 4 (GA4)

Niello supports Google AdSense by configuring the googleadclient parameter in the [params] block and Google Analytics 4 (GA4) by setting the ga parameter in the config.toml file as shown above.

# ShareThis

Niello support share your content to other platforms by [ShareThis](https://sharethis.com).

# Demo

A full demo is available here:	[https://www.angularcorp.com](https://www.angularcorp.com) 

# Buy a Coffee for Me

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/I2I1NFXI2)


