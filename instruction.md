You are given an Apache-style access log at:

/app/access.log

Create a file at:

/app/report.json

The file must contain valid JSON with exactly the following fields:

{
  "total_requests": <integer>,
  "unique_ips": <integer>,
  "top_path": "<string>"
}

Success Criteria

1. Count every log entry in /app/access.log and store the result in the `total_requests` field.
2. Count the number of distinct client IP addresses in /app/access.log and store the result in the `unique_ips` field.
3. Determine the most frequently requested URL path in /app/access.log and store the result in the `top_path` field.
4. Write valid JSON to /app/report.json.

Your solution is considered correct only if /app/report.json is valid JSON and all three fields contain the correct values derived from the access log.
