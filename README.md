## LLM4SciSci

This repository contains the training materials for the course "LLMs for science of science research" training, LMU, 2025.

#### Schedule
<font style="font-size:10">09:15 AM - 09:45 AM: Welcome & Intro<br>
10:00 AM - 11:00 AM: [Talk: Intro to LLMs]()<br>
11:00 AM - 11:15 AM: Break<br>
11:15 AM - 11:45 PM: [Talk: A gentle intro to Hugging Face and Python]()<br>
11:45 AM - 12:00 PM: Setup Colab<br>
12:00 PM - 12:30 PM: [Exercise: Running pipelines](https://github.com/Zak-Hussain/LLM4SciSci/blob/main/1_pipelines.ipynb)<br>
12:30 PM - 01:00 PM: Discussion: Find applications in small groups<br>
01:00 PM - 02:00 PM: Lunch<br>
02:00 PM - 03:00 PM: [Talk: Intro to transformers & embeddings]()<br>
03:00 PM - 03:30 PM: [Exercise: Clustering](https://github.com/Zak-Hussain/LLM4SciSci/blob/main/2_clustering.ipynb)<br>
03:30 PM - 03:45 PM: Break<br>
03:45 PM - 04:30 PM: [Talk: Intro to text generation]()<br>
04:30 PM - 05:00 PM: [Exercise: Labeling & retrieval](https://github.com/Zak-Hussain/LLM4SciSci/blob/main/3_labeling_retrieval.ipynb)<br>
05:00 PM - 06:00 PM: Open discussion<br>

### Resources
<a href="https://doi.org/10.3758/s13428-024-02455-8">Hussain, Binz, Mata, & Wulff (2024). A tutorial on open-source large language models for behavioral science. *Behavior Research Methods*, 1-24.
</a>
```
@article{hussain2024tutorial,
  title={A tutorial on open-source large language models for behavioral science},
  author={Hussain, Zak and Binz, Marcel and Mata, Rui and Wulff, Dirk U},
  journal={Behavior Research Methods},
  pages={1--24},
  year={2024},
  publisher={Springer}
}
```

[Hugging face documentation](https://huggingface.co/docs)<br>
[Hugging face book](https://transformersbook.com/)<br>
[But what is a GPT (3Blue1Brown)](https://www.youtube.com/watch?v=wjZofJX0v4M&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=5)<br>

### Installation

#### Hugging Face and Meta Llama License
1. Make sure you have a hugging Face account (https://huggingface.co/join).
2. Go to the [`meta-llama/Llama-3.2-3B-Instruct` model page](https://huggingface.co/meta-llama/Llama-3.2-3B-Instruct) and fill in the 'COMMUNITY LICENSE AGREEMENT' form at the top of the page to get access to the model (this may take a few minutes).

#### Google Colab and GitHub Repository
3. If you do not have a Google account, you will need to create one (this can be deleted after the workshop).
4. Navigate to Google Drive (https://drive.google.com/).
5. In the top-left, click New > More > Colaboratory. If you do not see Colaboratory, you may need to click "Connect more apps", 
search for 'Colaboratory', and install it. Then click New > More > Colaboratory.
6. Copy the following code snipped into the first cell of the notebook. Run it (```shift + enter``` or click &#9658; button) to mount your Google Drive to the Colab environment.
A pop-up will ask you to connect; click through the steps to connect your Google Drive to Colab. 
```
from google.colab import drive
drive.mount("/content/drive")
```
You will need to allow Google access to everything in your Google Drive for this to work, unfortunately. If you do not feel comfortable doing this, you can consider creating a new Google account for the purposes of this workshop. 
8. Create a second cell in your notebook using the "+ Code" button that appears when you hover your cursor right under the first cell. Copy and run the following code snippet in the second cell of your notebook to clone the GitHub repository to your Google Drive (you can also fork the repository instead if you prefer):
```
%cd /content/drive/MyDrive
!git clone https://github.com/Zak-Hussain/LLM4SciSci.git
```
9. Go back to your Google Drive and navigate to the folder "LLM4SciSci". You should see the relevant notebooks (.ipynb files) and data (it may take  a couple of minutes for the files to appear).

You are now ready to work through the exercises in the course! 
