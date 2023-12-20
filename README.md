# Description of SoldierPage_Backend Project
Led Battlefield 4 Soldier page development with Figma design. Used Node.js, React.js for backend/frontend. Created clone for a seamless user experience, blending design and cutting-edge tech.

## Project Dependencies

This project utilizes the following Node.js modules for seamless functionality:

- **Express:** A web application framework for Node.js, simplifying the creation of robust APIs.

- **Cors:** Middleware for handling Cross-Origin Resource Sharing (CORS), ensuring secure communication between frontend and backend.

### Installation

To install the required modules, use the following npm commands:

```bash
npm install express cors
```

## Data Storage Constants

Three constants are defined for storing data using key-value pairs:

1. **dataTable**
2. **domiananceTable**
3. **vehicles**

## API Endpoints

### GET API for Sending Data

To retrieve and send data, use the following GET API endpoint:

```plaintext
GET /api/data
```

## Image Serving Middleware

To serve images from the backend to the frontend, the following Express middleware is employed from the images directory:

```javascript
app.use('/images', express.static(path.join(__dirname, 'images')));
```


