# Beyond the Hype: A Realistic Look at Large Language Models

The following repo contains the materials for my talk delivered at GOTO Amsterdam 2024.

The repo contains the following:
* `/notebooks/rag-pdf-qa.ipynb` contains the code for the simple RAG pipeline I demoed during the talk. There are extensive notes in Markdown in this notebook to help you understand how to adapt this for your own use case.
* `talk-materials/talk-sources.md` contains all of the papers and other sources I used for this talk. It also contains all of my image credits.
* `talk-materials/beyond-the-hype.pdf` contains a copy of my slides.

# Steps for using the QA pipeline
1. Create a copy of `.env_sample` and rename it to `.env`
2. Get an OpenAI key from [here](https://platform.openai.com/api-keys)
3. Replace `key-here` with your API key in `.env` and save the file
4. Start a terminal window in the root of this repository
5. Enter `pip install -r requirements.txt`
8. Run all cells of the notebook