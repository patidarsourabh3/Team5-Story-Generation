
# Team 5 - Story Generation

### Team Members -     
    
    Lalit Gupta – 2021201018
    Sourabh Patidar - 2021201089
    Shankar Jetty Nag - 2021900019 
    Aaryan Singh - 2019114017 

### Link 

[Click to Download finetuned GPT2 model](https://drive.google.com/drive/folders/18rQ5ju85DNyYtKFa1CbQ4NkUWzUFiydp?usp=sharing)

### Submission Details

    This submission contains -
        - a dataset folder
        - a results folder
        - 3 ipynb files
        - README.md file
        - Final Presentation
    
    - Dataset folder contains the roc stories dataset which has 6 files train.src, train.tgt,valid.src, valid.tgt, test.src, test.tgt each corresponding to the train, validtion and test set for finetuning GPT-2.

    - Results folder contains a text file and few images. The images contain sample results and the text file "gpt2_res.txt" contains the results from finetuned gpt2 model on test set (input - "test.src").

    - 3 ipynb files 
        - file "finetuningGPT2-roc.ipynb" contains the code to finetune pre-trained GPT-2 model.
        - file "GPT2_story_gen.ipynb" contains code which takes any string as a input and generate the result using finetuned GPT2 model.
        - file "MVP_story_generation.ipynb" contains code which takes any string as a input and generate the result using pretrained mvp-story model.

    - To run "GPT2_story_gen.ipynb" download the finetuned model from above link and change the cell containing
    
        model = GPT2LMHeadModel.from_pretrained('/content/gdrive/MyDrive/gpt2_roc/') 

        to 

        model = GPT2LMHeadModel.from_pretrained('<folder_path>/gpt2_roc/')

    - All the libraries required to run the model are mentioned in notebook itself. 
