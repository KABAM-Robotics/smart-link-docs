# Smart+ Link API Documentation
## Overview

Smart+ Link is a cloud API gateway providing unified, robot-agnostic access to control and retrieve telemetry and sensors data (e.g. video, audio, lidar) from diverse robot platforms. Supporting various robot types and manufacturers through a standardized interface, it abstracts hardware differences to simplify development across heterogeneous robot fleets.

Third-party developers can leverage Smart+ Link to build cloud or on-premises applications including AI agents, custom user interfaces and dashboard, data analytics platforms, and industry-specific solutions. Whether integrating with existing systems like ERP and warehouse management software or creating specialized tools for manufacturing, healthcare, or retail, Smart+ Link provides the connectivity and data access needed to extend robot capabilities through a single, consistent API.

## Interface Types

Smart+ Link includes two types of interfaces:

1. REST API: Primarily used for issuing navigation commands and retrieving robot configurations
2. WebSocket API: Designed to receive real-time updates on robot and mission statuses

## Key Details

* **Base URL**: https://\<deploy-server-domain>/<device_id>
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