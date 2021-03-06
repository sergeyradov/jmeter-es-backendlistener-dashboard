# JMeter-ElasticSearch-BackendListener-Dashboard

### Supporting the author
[![patreon](https://c5.patreon.com/external/logo/become_a_patron_button.png)](https://www.patreon.com/bePatron?u=17797269)

#### *** This is still a work in progress - updated very frequently ***

## Why not simply use Grafana or Kibana?
Honestly, I use both. This also was an excuse for me to just fiddle around with React and Google Charts :smile: ! But seriously, there are some limitations into what you can achieve in Grafana and Kibana to visualize the results when using the ES Backend Listener. The funny thing is that the limitations are different in both solutions. I decided to create this to overcome these limitations.

## Roadmap
* Learn to manipulate React in a "best-practice" way :laughing:
  * Restructure project in an easy-to-understand and logical way
* Add all meaningful visualizations (charts) to the dashboard
  * Response time over time
  * Sent/Received bytes over time
  * Hits/error per second
  * Synthesis report
  * Number of threads over time
  * Error viewer
* Add error handling
* Add auto-refresh
* Add support for alerts
* Add multi-tenancy support
  * Login system
  * Permissions system
    * Restrictions to certain indices
    
## How to install

1. Clone the repository : ```git clone https://github.com/delirius325/jmeter-es-backendlistener-dashboard.git```
2. Open the folder in your favorite text editor
3. Start the app : ```yarn start```

## Contributing
Do not hesitate to contribute, all help is welcomed. If you don't want to commit code per say, but have some helpful critical feedback about project/code structure - just create an issue explaining the whole thing :smile:!
