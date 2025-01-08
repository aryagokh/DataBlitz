# DataBlitz - Opencode'24 - GeekHaven<br>
<b>Event:</b> DataBlitz - Opencode'24<br>
<b>Organized By:</b> AI/ML Wing of GeekHaven, IIIT Allahabad<br><br>
This competition challenged participants to solve the problem of Image Captcha Detection using machine learning techniques. The evaluation metric for this competition was accuracy.<br><br>


## Problem Statement
Design and implement a machine learning solution to detect and interpret captchas from images.<br>
The dataset can be found <a href="https://github.com/aryagokh/DataBlitz/blob/main/data.pdf">here</a>.
<br><br>

## Rules & Guidelines
### 1. Flex Your ML Skills
* Participants could either build models from scratch or fine-tune pretrained architectures.
* The goal was to demonstrate creativity and understanding of ML techniques.
* Image containing various alphanumeric captchas was present in the dataset.

### 2. Strict No-API Policy
* Usage of APIs like Hugging Face, ChatGPT, or Vision-Language Models (VLMs) was strictly prohibited.
* The competition emphasized learning and originality over simply utilizing prebuilt solutions.

### 3. Originality Counts
* Participants were encouraged to code, fine-tune, or creatively apply ML concepts to achieve the best results.
* Disqualifications were enforced for those who failed to comply with the rules.
<br><br>

## My Approach
### Model Selection
I fine-tuned the pretrained <a href="https://huggingface.co/microsoft/trocr-base-handwritten">`Microsoft/trocr-base-handwritten`</a> model, leveraging its capabilities for optical character recognition (OCR) to tackle the captcha detection problem.

### Training
I made a csv file containing image_paths and its associated captcha for training.<br>
I experimented with learning rates and dataset size for training.
More of which is explained <a href="https://github.com/aryagokh/DataBlitz/blob/main/Experiments_with_datasize_and_lr.pdf">here</a>.

## Challenges
* Noise and Variations: Captchas often included distortions, noise, and overlapping characters.
* Plateau in accuracy after a period of time.

## Results
Achieved competitive accuracy on the test dataset, showcasing the effectiveness of fine-tuning a powerful pretrained model.
Achieved 1st place due to this.

## Key Takeaways
* Gained hands-on experience in fine-tuning transformer-based OCR models.
* Successfully applied advanced ML techniques while adhering to strict competition guidelines.
<br><br>

Competition Link : <a href="https://www.kaggle.com/competitions/opencode-24-geek-haven/overview">DataBlitz - Opencode'24 - GeekHaven</a><br>
My Notebooks : <a href="https://www.kaggle.com/code/bharthee/0-71557-lb-datablitz">Kaggle_1st_Notebook</a>, 
               <a href="https://www.kaggle.com/code/bharthee/0-71428-lb-datablitz">Kaggle_2nd_Notebook</a>,
               <a href="https://www.kaggle.com/code/aryagokh/fork-of-0-71557-lb-datablitz">Kaggle_3rd_Notebook</a>


<b>Feel free to connect if you'd like to discuss this project or exchange ideas!</b><br>
<p align="center"><b><a href="https://www.linkedin.com/in/gokhale-arya">LinkedIn</a> | <a href="https://www.kaggle.com/aryagokh">Kaggle</a> | <a href="https://github.com/aryagokh/">GitHub</a></b></p>
