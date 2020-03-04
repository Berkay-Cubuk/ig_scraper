# ig_scraper v1.0.0
PHP based instagram scraper without login!

## installation
Just download ig_scraper.php and include the file.

## usage

1) Include ig_scraper.php
2) Create $ig variable
3) Type $ig = new IG_Scraper('type-your-username');
4) Start using ig scraper :D

## commands

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

## examples

1) Get json output
```
  $ig = new IG_Scraper('your-username');
  echo $ig->json();
```

## In the next update ig_scraper will able to get posts!
