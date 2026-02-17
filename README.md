# n11 Search Load Test

This repository contains a JMeter-based load test for the n11.com search functionality.

## Scope
- Home page load
- Search request via header (listing results)

## Tool
- Apache JMeter 5.6.3

## Test Configuration
- Users: 1
- Ramp-up: 1 second
- Redirect handling enabled
- Assertions based on HTTP response codes

## Notes
Search results are rendered client-side; therefore, content-based assertions were avoided to prevent false negatives.
