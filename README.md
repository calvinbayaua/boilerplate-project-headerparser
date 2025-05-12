# Request Header Parser Microservice

The **Request Header Parser Microservice** is an API that returns information about the user's device and connection by parsing the request headers. When a user accesses the `/api/whoami` endpoint, the server responds with details like IP address, language preferences, and software information.


## 📖 Learning Journey
This project was built while following [freeCodeCamp's Back End Development and APIs Course](https://www.freecodecamp.org/learn/back-end-development-and-apis).

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS
- **Backend:** Node.js (Express.js)

## 🎯 Features
- Parses and returns key client request header information:
  - `ipaddress`: User's IP address.
  - `language`: Language preference from the `Accept-Language` header.
  - `software`: User agent (OS and browser) from the `User-Agent` header.

## 🚀 Usage Examples

### Request
GET /api/whoami
**Response:**
```json
{
  "ipaddress": "127.0.0.1",
  "language": "en-US,en;q=0.9",
  "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64)"
}
```

## 📦 Installation & Setup
1. **Clone the repository:**
  ```sh
  git clone https://github.com/calvinbayaua/boilerplate-project-headerparser.git
  cd boilerplate-project-headerparser
  ```
2. **Install dependencies:**
  ```sh
  npm i
  ```
3. **Start the server**
  ```sh
  npm run start
  ```
