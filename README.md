## Project 3: **HTTP JSON API Client with API Key**

### ✅ Goal

Build a command-line app that fetches and displays JSON data from a real API that requires authentication via API key.

---

### 📋 Requirements

* [ ] Choose a public API that requires an API key:

  * [ ] OpenWeatherMap, NewsAPI, CurrencyAPI, etc.
* [ ] Store API key in config file or env variable
* [ ] Use `net/http` to make a GET request with headers
* [ ] Parse JSON response into Go structs
* [ ] Display response in a clean CLI format
* [ ] Handle:

  * [ ] API key errors (401)
  * [ ] Invalid input
  * [ ] Timeout/network errors

---

### 🌱 Optional Features

* [ ] Add CLI flags (e.g., `--city`, `--units`, `--category`)
* [ ] Cache responses in a local file
* [ ] Format output in tables or color
* [ ] Support multiple APIs via plugins

---

## 🧱 Suggested Folder Layout for Each

```
project-name/
├── main.go
├── internal/
│   ├── logic.go
│   ├── types.go
│   └── util.go
├── config/
│   └── config.go
├── go.mod
└── README.md
```
