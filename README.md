# zscore-aggregator

## Description
The zscore-aggregator is a Node.js application that aggregates z-scores for financial data. It uses Docker for containerization and provides an easy way to deploy and manage the application.

## Prerequisites
- Docker
- Docker Compose

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd zscore-aggregator
   ```

2. Run the setup script to install necessary dependencies:
   ```bash
   sudo bash setup.sh
   ```

## Usage
To start the application, run:
```bash
sudo docker-compose up --build
```

## Environment Variables
Make sure to set the following environment variables in the `.env` file:
- `PRIVATE_KEY_AGGREGATOR`: Your private key for the aggregator.

## License
This project is licensed under the MIT License.
