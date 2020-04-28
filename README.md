# This steps is only for GPT2-Fine-tuned-NLP Model Prediction

Note: Before you follow below steps you will have to inside this repository folder after cloning this repository.

1. First Install Python in your PC

2. git clone https://github.com/Manvith-koripally/GPT2-Fine-tuned-on-NLP.git
    (it will ask about github username and passowrd)

3. Install and create a virtual environment by the following step :
    ◦ sudo apt install virtualenv
    ◦ virtualenv gpt2_env --python=python3
    ◦ source gpt2_env/bin/activate (to activate the virtual environment)

4. cd GPT2-Fine-tuned-NLP

3. Open terminal and run below Command:

    pip3 install -r requirements.txt

4. Now run below command in terminal to genrate text using finetuned Model:

    python src/interactive_conditional_samples.py --model_name='1558M' --length=1023 --temperature=0.7 

