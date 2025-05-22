# Sentient Rolodex Backend

The Sentient Rolodex Backend is a Python-based RESTful API designed to manage contact information efficiently. It provides endpoints for creating, reading, updating, and deleting contact entries, facilitating seamless integration with frontend applications.

## Features

* **CRUD Operations**: Create, retrieve, update, and delete contact entries.
* **Modular Architecture**: Organized codebase with separate modules for controllers, models, routes, and middleware.
* **Middleware Support**: Custom middleware functions for request processing and validation.
* **API Documentation**: Comprehensive Postman collection (`postman_collection_sentient.json`) for testing and understanding API endpoints.

## Project Structure

```
Sentient-Rolodex-backend/
├── apiFeatures/               # Additional API functionalities
├── config/                    # Configuration files
├── controller/                # Request handlers
├── middleware/                # Middleware functions
├── models/                    # Data models
├── routes/                    # API route definitions
├── main.py                    # Application entry point
├── requirements.txt           # Python dependencies
├── postman_collection_sentient.json  # Postman API collection
└── .gitignore                 # Git ignore file
```



## Getting Started

### Prerequisites

* Python 3.x
* pip (Python package installer)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Suyashtiwary12/Sentient-Rolodex-backend.git
   cd Sentient-Rolodex-backend
   ```



2. **Create and activate a virtual environment** (optional but recommended):

   ```bash
   python -m venv venv
   On Windows: venv\Scripts\activate
   ```



3. **Install the dependencies**:

   ```bash
   pip install -r requirements.txt
   ```



### Running the Application

```bash
python main.py
```



The application will start and listen for incoming requests.

## API Documentation

A Postman collection is provided to demonstrate and test the available API endpoints.

1. **Open Postman**.
2. **Import the `postman_collection_sentient.json` file**.
3. **Use the collection to explore and test the API endpoints**.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Note: This README is based on the available project structure and standard practices. For more detailed information, please refer to the source code and comments within the repository.*

---
