# Amazon AWS IP Ranges

## Useful commands

1. List services on IP Ranges document for a given AWS region:
	`jq -r '.prefixes[] | select(.region=="us-gov-west-1") | .service' < ip-ranges.json  | sort | uniq`


## References

* https://docs.aws.amazon.com/general/latest/gr/aws-ip-ranges.html
