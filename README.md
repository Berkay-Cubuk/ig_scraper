# ig_scraper v1.0.1
PHP based instagram scraper without login or API!

## DISCLAIMER!
We do not take responsibility for anything that can happen, you take responsibility for all kinds of things you do. For business projects please contact with Instagram.

## Installation

### 1) Direct Download
Just download ig_scraper.php and include the file.

### 2) Composer
Packagist Link
https://packagist.org/packages/berkay-cubuk/ig_scraper

## Usage

1) Include ig_scraper.php
2) Create $ig variable
3) Type $ig = new IG_Scraper('type-your-username');
4) Start using ig scraper :D

## Commands

- json()
- biography()
- username()
- external_url()
- external_url_linkshimmed()
- followed_count()
- follow_count()
- full_name()
- has_channel()
- has_blocked_viewer()
- id()
- is_business_account()
- is_joined_recently()
- business_category_name()
- category_id()
- overall_category_name()
- is_private()
- is_verified()
- picture()
- picture_hd()
- connected_fb_page()

## Examples

1) Get json output
```
  $ig = new IG_Scraper('your-username');
  echo $ig->json();
```
2) Get full name
```
  $ig = new IG_Scraper('your-username');
  echo $ig->full_name();
```
3) Get biography
```
  $ig = new IG_Scraper('your-username');
  echo $ig->bioghraphy();
```

## Future plans

- Find user with id
- Get posts
