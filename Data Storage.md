# Data Storage

## Status
Proposal of how to handle data storage for the mobile application

## Context 
Data storage is essntial to store user data, product data, order history, session management, and analytics data.

## Decision
For the mobile application, both local storage and cloud-based storage would be used. The local storage would be used for offline access while cloud-based storage will be used to sync with the server when internet connection is avaiable.

## Consequences
Using both local storage and cloud-based storage adds complexity to the development,and also introduces more security risk for the user. It also creates a challenge when maintaining the application. Depending on the cloud storage provider, additional cost may be incurred.
