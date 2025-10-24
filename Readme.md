# MCP-Projects

```markdown
# 🚀 MCP-Projects

Welcome to **MCP-Projects**! This repository is dedicated to integrating the MCP (Multi-Channel Platform) framework with various messaging platforms and tools. The primary focus is to facilitate seamless communication and automation across channels, starting with WhatsApp integration using [Claude AI](https://www.anthropic.com/claude) and MCP.

---

## 📦 Introduction

**MCP-Projects** provides a flexible foundation for building messaging applications that interact with different platforms. For now, the core example is the WhatsApp integration, where messages are processed and responded to using the MCP server and Claude AI.

Whether you're looking to automate messaging workflows, build conversational bots, or experiment with cross-platform APIs, MCP-Projects gives you a starting point to extend and customize for your own needs.

---

## ✨ Features

- **WhatsApp Integration**: Connects directly to WhatsApp using [`whatsapp_api_client_python`](https://pypi.org/project/whatsapp-api-client-python/).
- **MCP Server**: Utilizes the `FastMCP` server for rapid message processing.
- **Environment Configuration**: Loads environment variables securely using `python-dotenv`.
- **Logging**: Built-in logging for easier debugging and monitoring.

---

## ⚙️ Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/<your-username>/MCP-Projects.git
    cd MCP-Projects
    ```

2. **Set up a Python virtual environment (optional but recommended)**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

    > **Note:** Ensure you have Python 3.7+ installed.

4. **Environment Variables**
    - Copy `.env.example` to `.env` and update it with your API keys and configuration.

---

## 🚀 Usage

The main entry point for WhatsApp integration is:

```
Whatssap-MCP/whatsapp_claude.py
```

To run the WhatsApp MCP server:

```bash
python Whatssap-MCP/whatsapp_claude.py
```

Make sure your `.env` file is correctly configured with the necessary credentials for WhatsApp and MCP.

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/my-new-feature`)
5. Open a Pull Request


---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

> **Connect, automate, and build with MCP-Projects!**
```


## License
This project is licensed under the **MIT** License.

---
🔗 GitHub Repo: https://github.com/selvaganesh19/MCP-Projects