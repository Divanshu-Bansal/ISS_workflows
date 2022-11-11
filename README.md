# New Relic Dashboards

The new relic dashboards for VehicleDescriptions Service are monitoring the SLIs & SLOs which are defined below in the table:

> **NOTE:** Default monitoring time on dashboard is 3 hours. This time frame can be changed from New Relic console as per the requirements.  

### SLIs & SLOs

| SLI         | Description                                          |Source                  |Aggregation Interval                 |SLO Target  |
| ----------- | -----------------------------------------------------|------------------------|-------------------------------------|------------|
| ​Latency (Single payload) | The portion of valid requests served faster than 250 ms for interfaces with a single payload. | [New Relic](https://onenr.io/07j9bYDrVQO)  | 28 days  | 99.9%  |
| ​Latency (Multi payload)  | The portion of valid requests served faster than 2 seconds for interfaces with multi payload. | [New Relic](https://onenr.io/0Zw06bea0jv)  | 28 days | 99.5%  |
| ​Availability  | The portion of valid requests served successfully.  | [New Relic](https://onenr.io/0BQ1pv3VKjx/) | 28 days  | 99.9%  |

## Availability

- **Birds Eye View:** This chart shows the availability percentage for all the requests which are made to the service. The availabilty of the service will be impacted if it is returning https code 500. 

- **Overall Availability(%):** This billboard shows the overall availability of our service in the time selected.
