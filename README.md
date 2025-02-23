
# URL Shortener 📏🚀  

A simple and efficient URL shortener built using Go. This application allows users to shorten long URLs and retrieve the original URLs using a unique short code.  

## Features  
- Generate short URLs for any given long URL  
- Redirect to the original URL using the short code  
- Simple and fast with minimal dependencies  

## Installation  

```sh
git clone https://github.com/yourusername/url-shortener.git
cd url-shortener
go mod tidy
go run main.go
```

## Usage  

### Shorten a URL  
Send a `POST` request to shorten a URL:  
```sh
curl -X POST http://localhost:8080/shorten -d '{"url": "https://example.com"}' -H "Content-Type: application/json"
```

### Redirect to Original URL  
Access the short URL:  
```sh
http://localhost:8080/{shortcode}
```

## Technologies Used  
- **Go** (Standard Library for HTTP handling)  

## Contribution  
Feel free to fork this repository and submit pull requests to improve the project.  

## License  
This project is licensed under the MIT License.  

---
