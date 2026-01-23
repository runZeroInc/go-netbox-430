# go-netbox

This is a fork of go-netbox v4.3.0 for use with NetBox servers equal to or later than 4.3.0.

This fork removes all response value validation during JSON unmarshalling to allow users with customized
NetBox configurations to run ingestion tasks without issue.