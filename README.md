# node-red-contrib-tdengine-consumer

## Installation

In your node-red directory:

```
npm install jbrass/node-red-contrib-tdengine-consumer
npm install @tdengine/websocket
```

## Usage

The plugin only supports STable topic or Query topic, which should be created by SQL:

```
create topic `stable_topic` as stable `stable_name`;
create topic `query_topic` as select * from `table_name`;
```
