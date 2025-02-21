# 📸 Random Unsplash Image API

A simple RESTful API built with **Node.js** and **Express** that serves random images fetched from **Unsplash**. Every time you hit the endpoint, it returns a random image in JSON format.

---

## 📑 Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoint](#api-endpoint)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

---

## ✨ Features
- Random image generation from a predefined list of Unsplash images.
- Lightweight and easy to set up.
- Simple JSON response format.

---

## ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SunnyKumar-code/ImageApi.git
   cd random-unsplash-image-api
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Create a JSON file with images:**
   Ensure you have a `unsplashImages.json` file with an array of image objects.

4. **Run the server:**
   ```bash
   node index.js
   ```

---

## 🚀 Usage

Start the server and open your browser or use Postman to visit:
```
http://localhost:5000/
```

You will receive a JSON response:
```json
{
  "id": "1",
  "url": "https://images.unsplash.com/photo-1735292626224-9cbee37fd0d6?crop=entropy&cs=srgb&fm=jpg&ixid=M3w2NzMxODN8MHwxfHJhbmRvbXx8fHx8fHx8fDE3NDAxMjg4NjR8&ixlib=rb-4.0.3&q=85",
  "title": "A blurry photo of two people on a motorcycle"
}
```

---

## 📡 API Endpoint

- `GET /` → Returns a random image from the list.

---

## 🧪 Testing

You can test the API using tools like [Postman](https://www.postman.com/) or CURL:

```bash
curl http://localhost:5000/
```

---

## 🤝 Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

