# !!! NOT SAFE FOR PRODUCTION !!!

# CORS Proxy Node app
Based on `cors-anywhere`.

## Usage
- `npm install`
- `npm run start`
- Your requests will be proxied, example: `http://localhost:8080/http://localhost:8000/api"`

## Environment variables
You can copy `.env.example` to `.env` and use the following:
- `CORS_PORT`
- `CORS_HOST`
