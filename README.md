# vuln-Rate-Limiting-Tester
Tests if rate limiting is implemented correctly by sending multiple requests in a short period and analyzing the responses. Reports on the limits from the response status codes and rate limit headers it receives. If no response is received from the target, the tool exits non-zero and reports no verdict. - Focused on Assess vulnerabilities in web applications by performing scans and providing detailed reports

## Install
`git clone https://github.com/ShadowGuard-AI/vuln-rate-limiting-tester`

## Usage
`python main.py <url> [-r REQUESTS_PER_SECOND] [-m MAX_REQUESTS] [-t TIMEOUT] [-u USER_AGENT] [-v]`

## Parameters
- `-h`: Show help message and exit
- `url`: The URL to test. Must start with http:// or https://, name a host, and use a valid port.
- `-r`: Number of requests to send per second (default: 10).
- `-m`: Maximum number of requests to send (default: 50).
- `-t`: Timeout for each request in seconds (default: 5). Must be greater than 0.
- `-u`: Custom User-Agent string to use.
- `-v`: Enable verbose logging.

## License
MIT License. See LICENSE for the full text.
