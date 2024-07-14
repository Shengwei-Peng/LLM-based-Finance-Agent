# LLM based Finance Agent

![agent](imgs/agent.png)

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

LLM based Finance Agent is a powerful tool that leverages large language models (LLMs) to automatically fetch news and predict historical stock prices to forecast future prices. This repository is designed to provide financial insights using state-of-the-art natural language processing (NLP) and machine learning techniques.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Shengwei-Peng/LLM-based-Finance-Agent.git
    ```
2. Navigate to the project directory:
    ```sh
    cd LLM-based-Finance-Agent
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Configuration

Configure the agent by editing the `config.json` file with your API keys and desired settings:
```json
{
    "news_api_key": "your_news_api_key",
    "genai_api_key": "your_genai_api_key",
    "model_name": "gemini-1.5-pro",
    "stock_symbol": "2330.tw",
    "days": 30
}
```

- `news_api_key`: Your API key for the news data provider (Apply [here](https://newsapi.org/)).
- `genai_api_key`: Your API key for Google Generative AI (Apply [here](https://aistudio.google.com/app/u/1/apikey?hl=zh-tw)).
- `model_name`: The name of the Google Generative AI model to be used.
- `stock_symbol`: The stock symbol to analyze.
- `days`: The number of days to consider for the analysis.

## Usage

1. Ensure that you have configured the config.json file as described in the [Configuration](#configuration) section.

2. Run the project using the following command:
    ```python
    python main.py
    ```

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact m11207330@mail.ntust.edu.tw
