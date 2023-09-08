# Text Summary And Translator
Web application that utilizes Flask and the OpenAI GPT-3.5 Turbo engine to summarize the text in different languages and read the summaries aloud.

# Prerequisites

Before you begin, make sure you have the following installed on your system:

1) Python
2) pip
3) jupyter notebook 

#Installation/Usage
1) Clone the repository
2) Go to the project directory
3) Start jupyter notebook
4) open AI_Summary_Translator.ipynb in the notebook
5) Change the API key to your own (not required for now as mine is still running)
6) Run the notebook cells to start the Flask application
7) Open a web browser and navigate to http://localhost:8082/. You can also click on the web link in the output of the last cell. If the port is already in use change the port in the last cell block.
   ![text_summary_p1](https://github.com/sudheersujay/TextSummary_translator/assets/42862988/ff2be9c3-b4e4-4202-a6da-b87e955fe34a)

8) Use the web interface in the notebook to enter text, select a language, and click "Summarize" to get a text summary.
    ![text_summary_p2](https://github.com/sudheersujay/TextSummary_translator/assets/42862988/29c5c852-bd00-4367-afed-468a3134a23f)

9) To listen to the summary in an audio format, simply click on the "Read Summary" button.

Additional Information
> The application uses the GPT-3.5 Turbo engine for text summarization.
> Feel free to customize the HTML template within the Jupyter Notebook to modify the look and feel of the web application.
