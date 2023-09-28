# Project: Data Transfer and Storage

## Description
This Python script performs the following tasks:
- Sends a POST request to a specified URL with provided data.
- Stores the response content in an Amazon S3 bucket.

## Configuration
Before using this script, make sure to configure the following:
- AWS S3 Configuration:
  - Replace `p_aws_access_key_id` with your AWS access key ID.
  - Replace `p_aws_secret_access_key` with your AWS secret access key.
  - Replace `p_bucket_name` with the name of your Amazon S3 bucket.
  - Replace `p_object_name` with the desired name for the S3 object to store the response.
- HTTP Request Configuration:
  - Replace `p_url` with the URL you want to send the POST request to.
  - Modify the `data` dictionary to include the necessary POST request data.
  - Adjust the `headers` dictionary if needed.

## Usage
1. Ensure you have Python installed on your system.
2. Install the required libraries using `pip install requests boto3`.
3. Execute the script by running `python main.py`.

## Dependencies
- Python 3.x
- Requests library for sending HTTP requests
- Boto3 library for interacting with AWS services

## License
This code is open source and available under the License file.
