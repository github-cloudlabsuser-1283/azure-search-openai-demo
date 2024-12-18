# Azure Search OpenAI Demo

This repository contains a demo application that integrates Azure Search with OpenAI's GPT-3 to provide advanced search and natural language processing capabilities.

## Prerequisites

- Azure Subscription
- Azure Search Service
- OpenAI API Key
- Node.js

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/azure-search-openai-demo.git
    cd azure-search-openai-demo/app/backend
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Create a `.env` file in the root directory and add your Azure Search and OpenAI credentials:
    ```env
    AZURE_SEARCH_API_KEY=your_azure_search_api_key
    AZURE_SEARCH_SERVICE_NAME=your_azure_search_service_name
    OPENAI_API_KEY=your_openai_api_key
    ```

## Usage

1. Start the application:
    ```sh
    npm start
    ```

2. Open your browser and navigate to `http://localhost:3000` to access the demo.

## Features

- **Search Integration**: Leverage Azure Search to index and search your data.
- **Natural Language Processing**: Use OpenAI's GPT-3 to understand and process natural language queries.
- **Interactive UI**: A user-friendly interface to interact with the search and NLP capabilities.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [yourname@yourdomain.com](mailto:yourname@yourdomain.com).
