# Managing permissions

## Status
We are proposing on how to implement the permissions required to access device features to meet app requirements.

## Context
Permissions are required to make sure that the application can access the required device features and user data to provide an excellent user experioence. The permissions which the app requires include Location, Storage, Push Notifications, and Internet connection.

## Decision
We decided to implement permission within the limits of the app, making sure that permissions are requested only when necessary and that users are given a clear explanation with each request.

## Consequences
If permissions are porrly explained or they get too intrusive, user fruestation and dissatisafaction would increase. Some users may deny permissions requests which could result in app crashes, user confuion, and abandoned task. It is also possible to violate permission guidelines which could resut in the app to get rejected by the app store.
