# vega-dataflow-examples

Example applications driven by Vega dataflows.

The [Vega](https://github.com/vega/vega) language uses a JSON syntax for
describing interactive visualizations. These JSON specifications are then
compiled to a reactive dataflow runtime. As of Vega version 3.0, the dataflow
runtime is a stand-alone library, allowing developers to build dataflows
directly, or author new high-level languages that use the same runtime.

This repository contains examples of how to build reactive data visualizations
directly using [vega-dataflow](https://github.com/vega/vega-dataflow) and
related modules. The examples here demonstrate use of the JavaScript API for
creating and connecting dataflow operators.

See [vega-runtime](https://github.com/vega/vega-runtime) for a JSON syntax
for serializing dataflow graph descriptions.

## Instructions

1. Install dependencies via `npm install`.
2. Build the Vega dataflow code via `npm run build`.
3. Launch a local web server in the top-level directory (e.g., `python -m SimpleHTTPServer 8000`).
4. Load the examples in your browser (e.g., at `http://localhost:8000/examples/`).
