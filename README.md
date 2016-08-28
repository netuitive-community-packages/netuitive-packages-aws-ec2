#netuitive.packages.aws.ec2 1.4.3

For detailed information on this package, please refer to the [online documentation](https://help.app.netuitive.com/Content/Misc/Datasources/AWS/new_aws_datasource.htm).

##Release History

###Version 1.4.3

* Updated package compatibilities.

###Version 1.4.2

* Bug fix for the multi-metric widgets on the element detail page.

###Version 1.4.1

* Bug fix: Events widget was not working correctly on the element detail page.

###Version 1.4.0

* Improved the "AWS EC2 - Elevated CPU Activity (Normal Network Activity)" policy; it will no longer fire if the CPU value is less than 20%.

###Version 1.3.0

* Added EC2-specific element detail page.
* Changed "sum" to "avg" on summary dashboard widgets.

###Version 1.2.0

* Added new policy, "AWS EC2 - CPU Threshold Exceeded".
* Defined units for the metrics

###Version 1.1.1

* Removed reference to obsolete metric.

###Version 1.1.0

* Added summary dashboard.

###Version 1.0.0

* Initial production release of the package for monitoring AWS Elastic Compute Cloud (EC2) resources.
