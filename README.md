# Sensor Data Analysis

Simple pandas project.

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```bash
python process_sensor_data.py
```

## Files

- `sensor_data.xlx`: Input data
- `process_sensor_data.py`: Analysis script
- `sensor_data_analyzed.xlx`: Output results

## What It Does

1. Loads XLX data
2. Cleans missing values
3. Calculates averages by equipment
4. Flags high temperature readings (>50°C)
5. Exports results

## Requirements

- Python 3.7+
- pandas
