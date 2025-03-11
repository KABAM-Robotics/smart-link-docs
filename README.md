# Smart+ Link API Documentation
## Overview

Smart+ Link is a cloud API gateway providing unified access to control robots and retrieve telemetry and sensor data (e.g. video, audio, lidar). The service offers a unified interface for interacting with Smart+ enabled robots, simplifying integration across multiple platforms.

## Interface Types

Smart+ Link includes two types of interfaces:

1. REST API: Primarily used for issuing navigation commands and retrieving robot configurations
2. WebSocket API: Designed to receive real-time updates on robot and mission statuses

## Key Details

* **Base URL**: https://<deploy-server-domain>/<device_id>
* **Authentication**: Bearer Token in the Authorization header
* **Content-Type**: JSON
* **Response Format**: JSON


**Note:** device_id is the unique identifier for each robot and must be included as a prefix for all API endpoints.

## Features

* Robot control and navigation
* Camera and sensor data access
* Mission management and scheduling
* Real-time status monitoring
* Configuration management
* Map navigation and localization