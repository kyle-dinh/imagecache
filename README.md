# Intervention Image Cache

Folk from [Intervention Image Cache](https://github.com/Intervention/imagecache)

## Folk story

I was want to use [Intervention Image URL Manipulation](http://image.intervention.io/use/url) but with source files from Laravel Storage (S3 driver in my case). So I made a minor change to load files from Storage beside configured paths.

## Installation

Update your composer.json with VCS repository

    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/kyle-dinh/imagecache"
        }
    ],
    "require": {
        "intervention/imagecache": "dev-master"
    },

## License

Intervention Imagecache Class is licensed under the [MIT License](http://opensource.org/licenses/MIT).
