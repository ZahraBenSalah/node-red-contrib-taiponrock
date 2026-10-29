# node-red-contrib-taiponrock

## Overview

This node forcibly replaces the input payload with the constant string `"Taiponrock"`.

Regardless of the input value, the node always returns `"Taiponrock"`. For example, if the input payload is `"Hello World"`, the output payload will be `"Taiponrock"`.

This node is based on the standard Node-RED example node that converts strings to lowercase using the JavaScript `toLowerCase()` method. The original processing logic has been replaced with a simple operation that returns a constant string.

## How to use

1. Add an Inject node to your flow.
2. Add the `taiponrock` node.
3. Add a Debug node.
4. Connect them in this order: `Inject → taiponrock → Debug`.
5. Deploy the flow and click the Inject button.
6. Open the Debug sidebar to see the output: `"Taiponrock"`.

The node always returns `"Taiponrock"`, regardless of the input payload.