# Campsite Review and Rating System

This project is built using the following tools and technologies:

- **Node.js**: Backend runtime environment.
- **Express.js**: Web application framework for Node.js.
- **MongoDB**: NoSQL database for storing data.
- **EJS**: Embedded JavaScript templates for server-side rendering.
- **Cloudinary**: Cloud-based image management service.
- **Mapbox API**: API for integrating maps and location-based services.

## System Features

The system's key features include:

- **Campground Management**: Users can add new campgrounds to the system.
- **Rating and Review**: Users can rate and review campgrounds.
- **Location Viewing**: Integrated Mapbox API for viewing campground locations.
- **Cloud-Based Image Uploads**: Cloudinary is used for managing image uploads.
- **Session Management**: Implemented session management for security purposes.

## Usage

To run the project locally:

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Set up MongoDB credentials.
4. Set up Cloudinary credentials in .env file.
   ```
        //Cloudinary credentials
        CLOUDINARY_CLOUD_NAME=your_cloud_name
        CLOUDINARY_KEY=your_cloudinary_key
        CLOUDINARY_SECRET=your_cloudinary_secret

        //Mapbox API token
        MAPBOX_TOKEN=your_mapbox_token
   ```
6. Run the server using `node app.js`.





