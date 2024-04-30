# NER (Named Entity Recognition)

## Setup

To set up the project, follow these steps:

1. Install the required dependencies by running the following command in your terminal:

    ```bash
    pip install -r requirements.txt
    ```

## How to run

To run the project, follow these steps:

1. Set the required environment variables by exporting the following values in your terminal:

    ```bash
    export OPENAI_API_KEY="sk-..."
    export OPENAI_API_ORG="org-..."
    ```

    Replace the `sk-...` and `org-...` placeholders with your actual API key and organization ID.

2. Execute the `run.sh` script by running the following command in your terminal:

    ```bash
    bash run.sh
    ```

    This will start the NER process using the specified API key and organization ID.

## Expected output

```bash
Text: Cựu tổng thống Trump gặp riêng ông DeSantis cuối tuần trước, lần đầu tiên
từ khi thống đốc Florida rời cuộc đua vào Nhà Trắng hồi tháng 1.
Entities: [('Trump', 'PERSON'), ('DeSantis', 'PERSON'), ('Florida', 'LOCATION'),
('Nhà Trắng', 'LOCATION')]
```

## Additional information

- <https://spacy.io/usage/large-language-models>
