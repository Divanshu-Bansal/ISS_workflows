## New Relic Dashboards

The new relic dashboards for VehicleDescriptions Service are monitoring the SLIs & SLOs as defined below in the table:

> **NOTE:** Default monitoring time frame for dashboard is 3 hours. This time frame can be changed from New Relic console as per the requirement  

### SLIs & SLOs

| SLI                       | Description                                              |Aggregation Interval        |SLO Target  |
| ----------------- | ---------------------------------------------------------------- | ------- | ---------- |
| ​Availability     | The portion of valid requests served successfully                | 28 days | 99.9%  |
| ​Latency (Single payload) | The portion of valid requests served faster than 250 ms for interfaces with a single payload | 28 days | 99.9%  |
| ​Latency (Multi payload)  | The portion of valid requests served faster than 2 seconds for interfaces with multi payload | 28 days | 99.5%  |


### Availability

- **Birds Eye View:** Chart showing the availability percentage for all the different types of requests which are made to the service. The availabilty of the service will be impacted if `HTTP status code >= 500`
- **Overall Availability(%):** Billboard showing the percentage of overall availability of our service
- **Overall SLO Attainment:** Billboard showing the percentage of overall SLO attainment with respect to availability of our service
- **Requests:** Table showing the details about the total number of requests, valid requests out of total requests, invalid requests out of total requests, number of vehicles processed, number of payload with errors and availability percentage for all different type of requests
- **Errors (Impacting Availability SLO) [CHART]:** Chart showing the percentage of requests having `HTTP status code >= 500` at a particular time
- **Errors (Impacting Availability SLO) [TABLE]:** Table showing the details about the HTTP status code, error name, error message and number of the errors for the requests having `HTTP status code >= 500` 
- **Client Errors [CHART]:** Chart showing the percentage of requests having `HTTP status code >= 300 and HTTP status code < 500` at a particular time
- **Client Errors [TABLE]:** Table showing the details about the HTTP status code and the number of errors occured for different type of requests having `HTTP status code >= 300 and HTTP status code < 500`
- **Vehicle Count:** Chart showing the number of vehicles proccessed at a particular time for different type of requests
