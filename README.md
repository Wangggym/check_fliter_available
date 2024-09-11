# API Request Field Checker

## Overview

The API Request Field Checker is a web-based tool designed to help developers and testers validate API responses and analyze the effects of different parameter values on API outputs. It provides an intuitive interface for parsing curl commands, sending API requests, and comparing results using AI-assisted analysis.

![image](https://github.com/user-attachments/assets/23db2072-0442-417c-b433-4188e403d097)

## Features

1. **Curl Command Parsing**: Easily input curl commands to automatically extract and display URL parameters and headers.

2. **Dynamic Request Modification**: Edit URL parameters and headers before sending requests.

3. **API Request Sending**: Send GET requests to APIs with the ability to bypass CORS restrictions using a proxy.

4. **Results Display**: View API responses in a formatted, interactive JSON viewer.

5. **AI-Assisted Analysis**: Utilize OpenAI's GPT model to generate comparison functions for specific fields in the API response.

6. **Validation Testing**: Automatically test multiple parameter values and compare results to identify effective filters.

7. **Local Storage**: Save curl commands, API keys, and other inputs for convenience across sessions.

## How to Use

1. Enter a curl command in the provided textarea.
2. Click "Parse and Send" to extract parameters and headers, and automatically send the request.
3. View the results in the expandable "Results" section.
4. Select specific content from the results for AI analysis by clicking on the lines you want to include.
5. Enter your OpenAI API key, fields to validate, and validation codes.
6. Click "Start AI Analysis" to generate a comparison function and perform validation tests.
7. View the validation results in the table at the bottom of the page.

## Requirements

- Modern web browser with JavaScript enabled
- Internet connection for making API requests and accessing OpenAI's API
- OpenAI API key for AI-assisted analysis

## Setup

1. Save the HTML file to your local machine or host it on a web server.
2. Open the file in a web browser.
3. You may need to request temporary access to the CORS Anywhere demo server at https://cors-anywhere.herokuapp.com/corsdemo to enable API requests.

## Notes

- The tool uses a CORS proxy (cors-anywhere) to bypass CORS restrictions. For production use, consider implementing your own proxy server.
- Ensure you have permission to use and test the APIs you're working with.
- Keep your OpenAI API key confidential and avoid sharing it publicly.

## Limitations

- Currently supports GET requests only.
- Relies on external services (CORS Anywhere and OpenAI API) which may have usage limits or require additional setup.

## Contributing

Contributions to improve the tool are welcome. Please submit issues or pull requests on the project's repository.

## License

[Specify the license under which this tool is released]
