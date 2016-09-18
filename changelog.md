# Changelog

### 1.2.1
- A client id [is now required](https://blog.twitch.tv/client-id-required-for-kraken-api-calls-afbb8e95f843) for Twitch API calls. Make sure your Twitch client id is set in either ```.env``` using the ```TWITCH_KEY``` variable, or directly in ```config/twitch-api.php```.

### 1.2.0
- Functions using the $option parameter has been fixed. This had to do with how headers were constructed in HTTP requests to the Twitch API using Guzzle.
- The Twitch API is now using https by default. Replacing http with https is no longer necessary.

### 1.1.0
- Function names are more friendly.

### 1.0.1
- Packagist support

### 1.0.0
- First release