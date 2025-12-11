tequ-node-red-plotly-create
=====================

Create Plotly.js chart.

## Install

Run the following command in your Node-RED user directory - typically `~/.node-red`

        npm install Lapland-UAS-Tequ/tequ-node-red-plotly-create

## Information

Creates Plotly.js chart to be used in Node-RED Dashboard 2.0.

Config and layout can be configured.

Input for this node should be either
1. Dashboard 2.0 UI control node output 
2. Message payload with value "reload"

This node has one output:
- Message to chart-node
