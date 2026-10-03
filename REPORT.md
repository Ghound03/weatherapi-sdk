# Voxgig SDK Generator – Developer Experience Report

## Overview

I used the Voxgig SDK Generator to attempt to generate a Python SDK for WeatherAPI.com.

The API specification used was Weather API version 1.0.2, provided through SwaggerHub as a Swagger 2.0 specification.

I tested the generator on Windows using Node.js v24.21.0 and npm v11.9.0.

The work was time-boxed as requested.

## What I Did

I downloaded the WeatherAPI Swagger specification and attempted to generate a Python SDK using:

```bash
npm create @voxgig/sdkgen -- weatherapi --def weatherapi.json --target 


