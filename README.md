# dockerized-prometheus-cloudwatch-logging

prerequisites
* iam instance role w/attached role to grant `cloudwatch:PutMetricData`

if you don't do the above, you'll need to modify `docker-compose.yml` to also pass in `AWS_ACCESS_KEY` and `AWS_ACCESS_KEY_ID`
