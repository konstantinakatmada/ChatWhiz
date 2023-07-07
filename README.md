# ChatWhiz

## A Chatbot Project with OpenAI LLMs API Integration

Welcome to the self-hosted chatbot project! This project aims to create a customizable chatbot by leveraging OpenAI's Language Models (LLMs) API while retaining ownership and control over the data and behavior.

## Project Overview

The project consists of a Python-based chatbot application built with Flask, a lightweight web framework. The chatbot interacts with users by processing their input and generating responses using the OpenAI LLMs API. The core functionality of the chatbot is controlled by your logic and parameters, providing a tailored user experience.

## Features

- **Customizable Behavior:** You have the freedom to define the chatbot's code and behavior based on your own logic and requirements. This allows you to create a chatbot that aligns with your specific use case and caters to your target audience.

- **Integration with OpenAI LLMs API:** The OpenAI LLMs API serves as the underlying language processing technology for the chatbot. By integrating with the API, you can leverage OpenAI's powerful models for generating responses, making the chatbot more intelligent and context-aware.

- **Data Ownership:** You retain ownership of the data used by the chatbot. Portions of the data are delegated to OpenAI's model for processing, but you maintain control over your data and its usage within the chatbot.

- **Pay-per-Use Model:** The cost structure of the project follows a pay-per-use or pay-per-token model. You are billed based on the number of tokens processed by the OpenAI LLMs API. Refer to OpenAI's official documentation or contact their sales team for specific pricing details.

## Getting Started

1. **Installation:** Clone this repository to your local machine and navigate to the project directory.

2. **Setup Environment:** Create a virtual environment and activate it.

   ```shell
   $ python3 -m venv venv
   $ source venv/bin/activate
   
3. **Install Dependencies:** Install the required Python packages.


   ```shell
   $ pip install -r requirements.txt
   ```


4.  **OpenAI API Configuration**: Sign up for an OpenAI account and obtain the necessary API credentials. Configure the API credentials by setting the environment variables OPENAI_API_KEY with your API key.

5.  **Run the Application**: Start the Flask development server.

  ```shell
  $ flask run
  ```


6.  **Access the Chatbot**: Open your web browser and visit http://localhost:5000 to access the chatbot interface.

## Further Customization

Feel free to modify the code and logic to suit your specific needs. You can enhance the chatbot's behavior by training or fine-tuning OpenAI's models using your own data. Refer to OpenAI's documentation for details on training and fine-tuning options.

## Disclaimer

Please be aware that OpenAI's models are continuously evolving, and it's important to stay updated with any changes or guidelines provided by OpenAI regarding the usage of their models and APIs.

## License

This project is licensed under the MIT License.





