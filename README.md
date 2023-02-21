# Movie Screenplay Generation

Built a pipeline, which, when given a prompt, generates a portion of a movie script. 

## Project

- Scraped the movie scripts of horror genre from [Internet Movie Database](https://imsdb.com/) using `Beautiful Soup`.
- Loaded the pretrained `GPT2Tokenizer` and `GPT2LMHeadModel`.
- Tokenized the scripts with a block size of `512` and a batch size of `6`.
- Trained the model for 3 epochs with `AdamW` optimizer.
- Saved the model files and config file into [this](https://drive.google.com/drive/folders/1jq21-dni3H_79-g64uEFh_E6DbcU3dds?usp=share_link) directory.
- Built a pipeline to generate the script, given a prompt, for demonstration purposes [here](./horror_script_generation.ipynb).
