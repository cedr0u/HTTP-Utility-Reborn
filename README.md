# HTTP-Utility-Reborn
HTTP Utility Reborn Plugin for MCreator

For : NeoForge 1.21.1 / 1.20.1
Forge 1.20.1 / 1.19.4 / 1.19.2 / 1.18.2 / 1.16.5 / 1.14.4
Fabric 1.20.1 / 1.19.2

This plugin was originally developed by @ddemile10 and has been upgraded by @cedr0u and before by @mydev1. All credits for the original creation go to @ddemile10. Icon by Flowicon.

### !! attention, errors caused by the POST request are possible, I'm currently working on it, if you want to contribute you are welcome !!

## About the Plugin
The HTTP Utility plugin allows you to make HTTP requests directly from your Minecraft mod. This can be useful for communicating with external APIs, fetching data, or sending information to a server.

## Features
- **HTTP GET Request**: Create and send an HTTP GET request to a specified URL.
- **HTTP POST Request**: Create and send an HTTP POST request with a JSON body to a specified URL.
- **Add Header**: Add custom headers to your HTTP requests.
- **Get Response**: Retrieve the response from an HTTP request.

## How to Use
1. **Create an HTTP GET Request**:
  - Use the block to specify the URL for the GET request.
  - Example: `Create an HTTP GET request to url "https://api.example.com/data"`

2. **Create an HTTP POST Request**:
  - Use the block to specify the URL and JSON body for the POST request.
  - Example: `Create an HTTP POST request to url "https://api.example.com/data" with json body '{"key": "value"}'`

3. **Add Headers to Requests**:
  - Use the block to add headers to your HTTP requests.
  - Example: `Add a header named "Authorization" with value "Bearer token" on request`

4. **Send Requests and Get Responses**:
  - Use the block to send the request and retrieve the response.
  - Example: `Send the HTTP request and get response`

This plugin is a powerful tool for mod developers looking to integrate external data and services into their Minecraft mods. Enjoy using the HTTP Utility plugin!