+++
# default attributes for an incident.
#
title = "2017-08-01 Sự cố mạng toàn DC"
date = 2017-08-01T13:50:30+07:00

# severity: represents the impact of 
# your system due to the current incident.
# This is the list of supported severities:
#
# - under-maintenance
# - degraded-performance
# - partial-outage
# - major-outage
#
severity = "major-outage"

# affectedsystems: is a list of systems affected
# by the incident.
# Example:
# affectedsystems = ["API", "Build servers"]
#
affectedsystems = ["API", "Build servers"]

# resolved: marks an incident as resolved.
# It can be either true or false.
#
resolved = false
+++
