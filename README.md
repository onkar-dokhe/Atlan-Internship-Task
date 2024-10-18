
# Atlan-Internship-Task

Transportation App is a scalable platform that manages users, drivers, trips, payments, and real-time location services. It uses microservices architecture to handle distributed tasks efficiently.


## Overview

The Transportation App is a microservices-based application that facilitates communication between users and drivers, including trip management, payments, and real-time location updates. It leverages distributed services, caching for fast retrieval, and integrates with third-party APIs like Google Maps and Stripe for seamless user experience.




## Architecture
![architecture](https://github.com/user-attachments/assets/c50d099d-bfe2-4b48-b0aa-b41d1e6554ac)



## Features

- User and Driver Management
- Real-time Trip Tracking
- Location-based Services with Google Maps SDK & API
- Payment Integration using Stripe/PayPal
- WebSocket communication for driver connectivity
- Caching for fast access to driver and user location data




## Important

Replace the Google Maps API key with your own in `AndroidManifest.xml`

```console
<meta-data
        android:name="com.google.android.geo.API_KEY"
        android:value="your-google-maps-api-key"/>
```
