# Url Shortner

Basically a URL shortener is a service to generate, retrieve and delete short URLs mapped to real URLs like goo.gl and bit.ly.
We will need a couple of features in our shotener.

## 1. Shorten a URL with a custom keyword
We want the user to give in input:
- a URL
- a custom keyword

The base URL for short urls will be http://short.com.
And we want the system to give back to the user his short URL.

Here is some examples:
- example 1
-- input URL: http://looooong.com/somepath/newService
-- input keyword: S1
-- expected output: http://short.com/S1

- example 2
-- input URL: https://anotherlong.com/anypath/myPage
-- input keyword: S2
-- expected output: http://short.com/S2


## 2. Retrieve a shortened URL 
We want the user to give in input:
- a shortened URL
And to receive in output:
- the original URL

- example
-- input URL: http://short.com/S1
-- expected output: http://looooong.com/somepath/newService

