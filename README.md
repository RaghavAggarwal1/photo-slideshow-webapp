# Full Stack Social Slideshow Photo Sharing App

This project contains all the code necessary to deploy a photo sharing party slideshow app.

Features:

- REST API written in Go for posting photos, logging in, and retrieving photos to display on a big screen TV (see backendServer directory)
- Front end single page application written in VueJS. The front end contains three views: The login, the photo upload view and the big-screen display slideshow (see frontend directory)
- Lightweight application that designed for running on a laptop that monitors a directory for photos and uploads them to the API. (see imageAutomation)
  - This was designed for the specific purpose of a photo booth where a fixed camera was taking photos and putting them on a laptop. This is completely optional. The app works standalone with smartphones
- Dockerfile and Helm chart included for deployment to kubernetes

## Project Structure

<img src="http://img.youtube.com/vi/wqcg9w_Q0iA/mqdefault.jpg" alt="Watch the series" width="240" height="180" border="10" />

## How to install

1. use the helm chart to deploy after making your necessary changes
