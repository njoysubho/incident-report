# incident-report
It's a collection of reported outages.

One can learn a lot from incident reports of outages from large organization despite their effort to keep system up almost all the time. 

#### CloudFlare Outage that lasts 02 Nov 2023-04 Nov 2023
* Power failure in DC PDX-04.
* Although they have active-active DC setup but their Kafka and ClickHouse service were only supported via PDX-04. 
* They cite in the report that although they simulated partial DC outage they never simulated complete DC outage.
Read the source incident report - https://blog.cloudflare.com/post-mortem-on-cloudflare-control-plane-and-analytics-outage/

