---
layout: project
type: project
image: img/Screenshot 2023-08-29 at 2.31.46 PM.png
title: "Model in the Mirror"
date: 2023
published: true
labels:
  - Python
  - OpenAI
  - spaCy
  - GitHub
summary: "A python script that generates C-tests for language learning purposes."
---

<img class="img-fluid" src="img/Screenshot 2023-08-29 at 2.31.46 PM.png">

Model in the Mirror was a research project I completed with the Center for Language and Technology at UH Manoa. The purpose was to develop a script that creates "C-tests," which are language learning passages that the Center will use for an app that they are developing.

The script does the following:
1. Takes a text sample from most text formats (txt, pdf, epub, etc)
2. Inputs this text into OpenAI's ChatCompletion API with a prompt asking the model to generate 5 new passages from the base text.
3. Places the output into a list for processing.
4. Queries the model again and modifies the passage to a difficulty level and language the user inputs.
5. Queries the model to categorize the passage from a list of single-word topics.
6. Places the passage into a json database for long-term storage.
7. Uses spaCy NLP to separate the passage into sentences, and then tokens.
8. Surrounds the second half of every second word with astrixes, excluding the first sentence, proper nouns, numbers, and punctuation (as punctuation is a token).
9. Recombines the tokens into a string and sends the output to another json file.

Below is a link to the repository where all files are stored. The most relevant files include newgenerator or pdfscraper, which are the passage generators, any one of the beginner database files, and any one of the spacy files that convert the base passages to C-tests.
[Model in the Mirror Repo](https://github.com/llcit/model-mirror "llcit/model-mirror")

Additionally, [this](https://hushed-spiny-scaffold.glitch.me "H5P example") is a sample website that was used for language experts to test the C-tests.
