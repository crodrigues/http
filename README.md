# phpish/http

Convenience wrapper around [cURL](http://php.net/manual/en/book.curl.php).


## Requirements

* PHP 5.3+ with [cURL support](http://php.net/manual/en/book.curl.php).


## Namespace

`phpish\http`


## Functions

string __request__( string _$method_uri_ [, mixed _$query_ [, mixed _$payload_ [, array _&$response_headers_ [, array _$request_headers_ [, array _$curl_opts_ ]]]]] )


callback __client__( string _$base_uri_ [, array _$request_headers__ [, array _$curl_opts_ ]] )


## Usage and Quickstart Skeleton Project

See [phpish/http-skeleton](https://github.com/phpish/http-skeleton)