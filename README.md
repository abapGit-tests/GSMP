# GSMP
GSM Provider for the Generic Simple Metric Framework

This repository contains a syntactically correct example of a GSMP metric provider together with a sample implementation class.

The sample implementation class is not directly a part of the provider. You can pull the metric provider without including this class. But since the class is referenced in z_gsmp_example.gsmp.json it wouldn't be possible to activate the provider object without this class after importing it into your system.