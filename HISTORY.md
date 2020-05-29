## Release History

### Version next

### Version 2.1.0
* Add meta configuration for cloudwatch memory utilization metric
* Convert single elementType to elementTypes array in policy scope

### Version 2.0.0

* Refresh EC2 Summary and EC2 Element Detail dashboards

### Version 1.8.0

* Adjusted build to use metricly-cli for validation
* Convert computed metrics to new format

### Version 1.7.1

* Fix for network metrics match expression

### Version 1.7.0

* Updates to EC2 Summary dashboard

### Version 1.6.0

* Removed EC2 Metric Aggregation and EC2 Types widgets
* Updated Element Detail dashboard layout

### Version 1.5.0

* Updated dashboard layouts for gridstack

### Version 1.4.4

* Changed the CPU Threshold Exceeded policy to be disabled by default, as it can be noisy for some customers.

### Version 1.4.3

* Updated package compatibilities.

### Version 1.4.2

* Bug fix for the multi-metric widgets on the element detail page.

### Version 1.4.1

* Bug fix: Events widget was not working correctly on the element detail page.

### Version 1.4.0

* Improved the "AWS EC2 - Elevated CPU Activity (Normal Network Activity)" policy; it will no longer fire if the CPU value is less than 20%.

### Version 1.3.0

* Added EC2-specific element detail page.
* Changed "sum" to "avg" on summary dashboard widgets.

### Version 1.2.0

* Added new policy, "AWS EC2 - CPU Threshold Exceeded".
* Defined units for the metrics

### Version 1.1.1

* Removed reference to obsolete metric.

### Version 1.1.0

* Added summary dashboard.

### Version 1.0.0

* Initial production release of the package for monitoring AWS Elastic Compute Cloud (EC2) resources.
