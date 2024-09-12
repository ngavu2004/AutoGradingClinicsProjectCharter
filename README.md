# Auto Grading Clinics Project Charter with AI
This is a simple Python UI to autograde the Clinics project charters in bunch that saves the effort on manual work and ensure data security.

## Basic Features of this app
* Grading project charter using AI Models
* You can choose which part and which criteria you want to grade on, the program will break the text file(s) down to section and automatically generate prompts for the AI to grade on that criteria
* You can either import 1 file and get immediate result, or import whole folder of files and get result back as a csv file.
* Run locally, no need wifi and ensure data security
* Simple setup, just 3 steps

## Steps to run this app
### 1. Download Ollama
Go to this link: https://ollama.com/ . And download the ollama version appropriate to your OS.

### 2. Run Ollama
After downloading Ollama, please open the terminal and paste the following command.
```
ollama serve
```
Then hit Enter

### 3. Download this notebook and hit run all
Download this notebook and open it then hit Run all. If you don't have any program to run Jupyter Notebook, please don't worry, I will release an .exe version of this script soon.

### 4. This UI will open up and you can upload any file/folder you want
After upload and hit "Get feedback from AI model", please wait a while since it might take long time depend on the size of the file/folder you just upload.

![image](https://github.com/user-attachments/assets/49d9c2fc-08b5-48bd-a6d2-3f508bdb7383)

## Possible defects
* If you don't have the appropriate program to open Jupyter notebook, please turn on the noti for this repo since I will publish a version with .exe soon
* The program might take a while to run. This is due to the size of the file is to big or due to the GPU of your computer. I will apply prompt compression techniques to improve this problem soon.

## Future development
* Finetune Llama 3 on our lab's data to improve the accuracy. (This will happen if I can clean the data and engineer them to be a training set)
* Prompt compression to improve the efficiency of the model
* Improve on the UI of this app
* If you have any suggestion, please send an email to my ASU emai: thiquynh@asu.edu



