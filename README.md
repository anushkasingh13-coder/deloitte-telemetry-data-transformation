# deloitte-telemetry-data-transformation
# Deloitte Telemetry Data Transformation

A Python-based data transformation task completed as part of the Deloitte Technology Job Simulation on Forage.

## Overview

This project converts two different telemetry data formats into a single unified JSON structure.

### Formats handled

* **Format 1:** Device information and location are stored directly in the JSON object.
* **Format 2:** Device information is nested and the timestamp is provided in ISO 8601 format.

The program transforms both formats into the expected unified structure.

## Technologies Used

* Python
* JSON
* `datetime`
* `unittest`

## Features

* Converts Format 1 telemetry data
* Converts Format 2 telemetry data
* Converts ISO 8601 timestamps to milliseconds since Unix epoch
* Normalizes location information
* Validates the output using unit tests

## How to Run

Make sure Python is installed, then run:

```bash
python main.py
```

Expected result:

```text
Ran 3 tests

OK
```

## Project Context

Completed as part of the Deloitte Technology Job Simulation on Forage.

