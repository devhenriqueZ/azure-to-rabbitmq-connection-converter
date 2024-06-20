# Azure Service Bus to RabbitMQ AMQP Converter

## Overview

This repository hosts a web-based tool for converting Azure Service Bus connection strings to RabbitMQ's AMQP format. It operates entirely locally in your browser, ensuring that no data leaves your device, thus prioritizing user privacy and data security.

## Features

- **Local Processing:** All conversion operations are performed client-side, ensuring that sensitive connection string data remains private.
  
- **User-Friendly Interface:** Simple and intuitive web interface designed using HTML, JavaScript, and Bootstrap 4 for ease of use.
  
- **Two Output Formats:** Generates RabbitMQ AMQP connection strings suitable for both current and older versions (pre Erlang 26.0).

- **Copy to Clipboard:** Convenient buttons to copy the generated AMQP connection strings directly to your clipboard for easy integration.

## How to Use

1. **Input Azure Service Bus Connection String:**
   - Paste your Azure Service Bus or Event Hubs connection string into the provided text area on the web page.

2. **Convert:**
   - Click on the "Convert" button to generate RabbitMQ AMQP connection strings.

3. **Copy or Use:**
   - Use the "Copy To Clipboard" button next to each generated AMQP connection string to copy it for use in your applications.

## Installation

As this tool runs entirely in the browser, there is no installation required. Simply open `index.html` in your preferred web browser and start converting your Azure Service Bus connection strings.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

Special thanks to [Bootstrap](https://getbootstrap.com/) for providing the responsive web design framework used in this project.

---

**Disclaimer:** This is a static web application. All processing is done locally in your browser. No data from the form is sent to external servers or services, including Azure.