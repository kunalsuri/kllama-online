# ✅🦙Kllama: Your Private Chatbot Online

⚡ Your personal chatbot running on open LLM model(s) Online⚡

[![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/kunalsuri)](https://twitter.com/kunalsuri)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![GitHub language count](https://img.shields.io/github/languages/count/kunalsuri/kllama)
![GitHub top language](https://img.shields.io/github/languages/top/kunalsuri/kllama?color=yellow)
![GitHub Repo stars](https://img.shields.io/github/stars/kunalsuri/kllama)



<br>

> Author: Kunal Suri, Ph.D.
>
> Other Info: The symbol {✅🦙} for Kllama stands for OK, Llama (or) Kunal's llama! 😁🙏

<br>

## 🚀 How to use Kllama Online?
This application will be executed using open-source LLM models provided by services such as Replicate.com

### Table of Contents
1. [Prerequisites](#Prerequisites)
2. [Running Kllama via Models Online](#Running-Kllama-Online)

<br>

---


### Prerequisite Steps for using models online

To run the Kllama app online, the user needs an account in [Replicate.com](https://replicate.com/). Once this account is created, the user will get an API Key/ Token, which is needed to execute the prompt on the LLM. 

<br>

⚠️ Note: We are not affiliated with [Replicate.com](https://replicate.com) company; I simply found their service interesting and decided to use it.

<br>

**Steps**

1. Create an account in Replicate.com
2. Get the API token from your Replicate.com
3. Place the API token in the .streamlit/secrets.tom file
   > REPLICATE_API_TOKEN = "PUT YOUT TOKEN HERE"


To use this app, you need do the following steps:

1. **Download/ Replicate the Git Repo in your local machine**

   > We assume that you have cloned the Kllama repo on your local machine. If not, do the following:

```bash
git clone https://github.com/kunalsuri/kllama-online.git
```

<br>

⚠️ Recommendation: To keep their python installations for other projects clean, we recommend that the users create a new python virtual environment for the Kllama project and install the python packages via requirement.txt (in Step 3 below)

<br>

3. **Install the python packages needed to run the Kllama Online Chatbot**

> kllama-online.py application needs the following main packages: replicate, streamlit. They have been included to the requirements.txt and can be easily installed. To install the packages, go to the folder containing kllama-online and enter the below command:

```bash
pip install -r requirements.txt
```

<br>

---

### Running Kllama via Models Online

> As said before, running Kllama online needs the user to have an account in webservices such as [Replicate.com](https://replicate.com/) to use the open LLM models running there. Once the Prerequisite step run the following command

```bash
streamlit run kllama_online.py
```
   
<br>

✅ If configured and executed properly, the Kllama Chatbot will start running via the kllama-online.py app on your web browser and will be ready for your use.

For the Kllama (online version), the user can use the Llama2-7B model or Llama2-13B model that is available in the [Replicate.com](https://replicate.com) website. There are some trial credits available to the user and then the user may need to pay, based on the rules from Replicate.com.

<br>

---

## 🛡️Responsible AI 
:european_union: **EU's Guidelines on the responsible use of generative AI in research:** https://research-and-innovation.ec.europa.eu/news/all-research-and-innovation-news/guidelines-responsible-use-generative-ai-research-developed-european-research-area-forum-2024-03-20_en

<br>

⚠️ Note: In no circumstance shall the author(s) or copyright holder(s) be held liable for any claim, damages, or other liabilities arising from the utilization of this code, which incorporates several code snippets generated by artificial intelligence (AI), along with opne source contributions from other programmers sourced from GitHub and other platforms, pursuant to the terms outlined in the MIT License.



