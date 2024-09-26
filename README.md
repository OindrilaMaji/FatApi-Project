# FastApi-Project
# Asset Performance Dashboard API

## Overview
This project implements an Asset Performance Dashboard API using FastAPI and MongoDB. The API provides endpoints to manage asset data and gather insights into asset performance metrics.

## Structure
The project directory has the following structure:
- `app`: Contains the FastAPI application code.
- `tests`: Includes test cases for the API endpoints.
- `requirements.txt`: Lists the project dependencies.
- Other files and directories for project-specific requirements.

## Usage

### Setup
1. Install the project dependencies using pip:

2. Start the FastAPI application:

3. Visit `http://localhost:8000/docs` in your browser to access the interactive API documentation (Swagger UI).

### API Endpoints
- `GET /assets/`: Retrieve a list of all assets.
- `POST /assets/`: Create a new asset.
- `GET /assets/{asset_id}`: Get details of a specific asset.
- `PUT /assets/{asset_id}`: Update details of a specific asset.
- `DELETE /assets/{asset_id}`: Delete a specific asset.

### Test Cases
The test cases for API endpoints are provided in the `tests` directory.

### MongoDB Integration
The project integrates with a MongoDB database to store and manage asset data.

## Contribution
We welcome contributions to further enhance the functionality and features of the Asset Performance Dashboard API.

Please feel free to reach out if you have any questions or need further information.

