# Hello OpenShift

A simple Flask app for OpenShift demonstration.

## Features

- Responds at `/` with a greeting message
- `/health` endpoint for liveness/readiness probes
- Runs on port `8080` (OpenShift default)

## Running locally

```bash
pip install -r requirements.txt
python app.py
