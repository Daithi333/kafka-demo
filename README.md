# Kafka Demo

### Getting Started

Follow [Getting Started guide](https://developer.confluent.io/get-started/python) to set up cluster and create 
`getting_started.ini` config file. Add it to the root of the 'getting_started' directory

Navigate to getting_started directory: `cd getting_started`

 - Run `python ./producer.py getting_started.ini` to produce test events

 - Run `python ./consumer.py getting_started.ini` to consume events

 - To stop consuming events, use `Ctrl+C`
