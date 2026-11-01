# vuln-Rate-Limiting-Tester
Tests if rate limiting is implemented correctly by sending multiple requests in a short period and analyzing the responses. Reports on the limits from the response status codes and rate limit headers it receives. - Focused on Assess vulnerabilities in web applications by performing scans and providing detailed reports

## Install
`git clone https://github.com/ShadowStrikeHQ/vuln-rate-limiting-tester`

## Usage
`./vuln-rate-limiting-tester [params]`

## Parameters
- `-h`: Show help message and exit
- `-r`: Number of requests to send per second (default: 10).
- `-m`: Maximum number of requests to send (default: 50).
- `-t`: Timeout for each request in seconds (default: 5).
- `-u`: Custom User-Agent string to use.
- `-v`: Enable verbose logging.

## License
Copyright (c) ShadowStrikeHQ
