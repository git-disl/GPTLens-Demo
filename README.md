# GPTLens Demo
<img width="394" alt="Screenshot 2024-05-01 at 8 37 33 AM" src="https://github.com/git-disl/GPTLens-Demo/assets/72898301/788b9092-6be7-4e8a-81e5-b1a345bde63b">

GPT Lens is an LLM tool to check for security breaches in smart contracts. To learn more, go to : https://github.com/git-disl/GPTLens. This demo app provides a scenario-based walkthrough of how GPTLens utilizes LLMs to examine smart contract code and detect vulnerabilities.

## GPTLens introduction
GPTLens leverages Large Language Models (LLMs) like GPT-4 to enhance the security analysis of smart contracts. It addresses the critical need for effective smart contract vulnerability detection, which has become increasingly important with the prevalence of blockchain technology. GPTLens introduces a two-stage framework: generation and discrimination. In the generation stage, LLMs act as auditors to identify a broad spectrum of potential vulnerabilities. The discrimination stage then evaluates these findings to minimize false positives, significantly enhancing the accuracy and reliability of vulnerability detection(shown in the figure below).

<img width="900" alt="Screenshot 2024-05-01 at 8 42 39 AM" src="https://github.com/git-disl/GPTLens-Demo/assets/72898301/14bd5cd0-1c43-449f-a5f8-ec85dab4c46c">



Some key features of GPTLens include:
- **Dual-stage Analysis:** Utilizes generation and discrimination stages to identify and verify smart contract vulnerabilities.
- **LLM-driven Approach:** Completely driven by LLMs, requiring no specialist knowledge in smart contracts for initial assessments.
- **High Accuracy and Efficiency:** Designed to reduce false positives and enhance the detection process without compromising on performance.

## Installation

pip install -r requirements.txt

## Running GPTLens Demo

python src/gpt_lens_demo.py


## Sample Pages of GPTLens Demo
This demo shows the GPT-lens workflow

Demo app Coverpage:

<img width="600" alt="GPTLens Demo app cover page" src="https://github.com/git-disl/GPTLens-Demo/assets/72898301/78c45bbf-bd02-4e0a-a509-1cdf1cd88941">

Demo app showing GPTLens architecture step-by-step:

<video alt="GPTLens Demo introduction page" src="https://github.com/git-disl/GPTLens-Demo/assets/72898301/f0949519-bcc7-4d38-ac73-b7cf3e238f6a"></video>

Demo app displaying data pipelining:

<video alt="GPTLens Demo data loading page" src="https://github.com/git-disl/GPTLens-Demo/assets/72898301/749b7724-e0b3-43a6-ad7e-c890b441b1ac"></video>




## Acknowledgements

This mini-project, GPTLens, was developed by Yining Yuan in collaboration with the GIT DiSL group under the supervision of Prof. Dr. Ling Liu and PhD student Sihao Hu.

For more detailed information on GPTLens, please refer to the following resources:
- [GPTLens Paper](https://arxiv.org/pdf/2310.01152.pdf)
- [GPTLens Open Source Code](https://github.com/git-disl/GPTLens?tab=readme-ov-file)

For any technical questions regarding this project, please consult with Sihao Hu.



