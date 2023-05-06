# GPT-Reworder

## Welcome to this project

This project surpasses the length constraints of using OpenAI Chat-LLMs, such as ChatGPT, enabling you to converse with any long document. It expedites comprehension of the content and facilitates the acquisition of valuable insights. Compared with ChatPDF, it accommodates various file formats, including PDF, doc, docx, txt, and web URLs. The implementation of this project is straightforward to follow, expand, and efficient for integration into other applications.
The best use case is to re word long doccuments

## Dependencies

Please execute the following command in the terminal to install the required dependencies:

Python>=3.8

```shell
cd ChatLongDoc
pip install -r requirements.txt
```

## Usage

In the **demo.ipynb**, we provide a simple and clear procedure:

1. Please replace the first line of the `./openai_api_key.txt` file with your preferred OpenAI API Key. It will be read when the dependencies are loaded.
2. Enter the path to the local file you wish to chat with. Our program currently supports pdf, doc, docx, txt files, and web URLs. As a tutorial, you may try the `./example/example.pdf file`, which is a paper titled ["Attention Is All You Need"](https://arxiv.org/abs/1706.03762).
3. Once the file is loaded, our system will process the content of the document or web page and store the memorized information in `./memory` for future reference. A memory file is already available in the directory if you're using the example document.
4. Input your query and start chatting with the document.
