<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD041 -->

<p align="center">
    <h1 align="center">🧚🏻‍️ YiVal</h1>
</p>

<p align="center">
  <a aria-label="website" href="" target="_blank">
    Website
  </a>
  ·
  <a aria-label="producthunt" href="" target="_blank">
    Producthunt
  </a>
·
  <a aria-label="producthunt" href="" target="_blank">
    Documentation
  </a>

</p>

<p align="center">
    <h5 align="center">⚡ Build any Generative AI application with evaluation
        and improvement ⚡</h5>
</p>

<!-- markdownlint-disable-next-line MD013 -->
👉 Follow us: [![Twitter](https://img.shields.io/twitter/url/https/twitter.com/YiValai.svg?style=social&label=Follow%20%40YiVal)](https://twitter.com/yivalloveaigc) |
[![Discord](https://dcbadge.vercel.app/api/server/6Q6Rgwrstw?compact=true&style=flat)](https://discord.gg/6Q6Rgwrstw)

[![Downloads](https://static.pepy.tech/badge/YiVal/month)](https://pepy.tech/project/YiVal)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub star chart](https://img.shields.io/github/stars/YiVal/YiVal?style=social)](https://star-history.com/#YiVal/YiVal)
[![Dependency Status](https://img.shields.io/librariesio/github/YiVal/YiVal)](https://libraries.io/github/YiVal/YiVal)
[![Open Issues](https://img.shields.io/github/issues-raw/YiVal/YiVal)](https://github.com/YiVal/YiVal/issues)

## 🤔 What is YiVal?

YiVal is an GenAI-Ops framework that allows you to iteratively tune your **Generative
 AI model metadata, params, prompts and retrieval configs** all at once with your
 preferred choices of test dataset generation, evaluation algorithms and improvement
strategies.
  <!-- markdownlint-disable-next-line MD013 -->
[Check out our quickstart guide!](https://github.com/YiVal/YiVal/blob/master/demo/tutorial_notebook/tutorial.md) →

## 📣 What's Next?

### Expected Features in Sep

- [x] Add ROUGE and BERTScore evaluators
- [x] Add support to midjourney
- [x] Add support to LLaMA2-70B, LLaMA2-7B, Falcon-40B,
- [x] Support LoRA fine-tune to open source models

## 🚀 Features

|          | 🔧 Experiment Mode:                                           | 🤖 Agent Mode (Auto-prompting):                               |
| -------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Workflow | Define your AI/ML application ➡️ Define test dataset ➡️ Evaluate 🔄 Improve ➡️ Prompt related artifacts built ✅ | Define your AI/ML application ➡️ Auto-prompting ➡️ Prompt related artifacts built ✅ |
| Features | 🌟 Streamlined prompt development process<br/> 🌟 Support for multimedia and multimodel<br/> 🌟 Support CSV upload and GPT4 generated test data<br/>🌟 Dashboard tracking latency, price and evaluator results<br/> 🌟 Human(RLHF) and algorithm based improvers <br/>🌟 Service with detailed web view<br/>🌟 Customizable evaluators and improvers | 🌟 Non-code experience of Gen-AI application build<br/>  🌟 Witness your Gen-AI application born and improve with just one click |

## Model Support matrix

We support 100+ LLM ( gpt-4 , gpt-3.5-turbo , llama e.g.).

Different Model sources can be viewed as follow

| Model        | llm-Evaluate |Human-Evaluate|Variation Generate|Custom func|
|--------------| ---- | ---- | ---- |--------------|
| OpenAI  | ✅  | ✅  | ✅  |✅|
| Azure   | ✅  | ✅  | ✅  |✅|
| TogetherAI | ✅ | ✅ | ✅  |✅|
| Cohere | ✅ | ✅ | ✅ |✅|
| Huggingface | ✅ | ✅ | ✅ |✅|
| Anthropic | ✅ | ✅ | ✅ |✅|
| MidJourney | | ✅ |  |✅|

To support different models in custom func(e.g. Model Comparison) , [follow our example](https://github.com/YiVal/YiVal/blob/litellm_complete/demo/configs/model_compare.yml)

To support different models in evaluators and generators , [check our config](https://github.com/YiVal/YiVal/blob/litellm_complete/demo/configs/headline_generation.yml)

## Installation

### Requirements

- Python 3.10+ environment
- OpenAI API Keys (Add `OPENAI_API_KEY` as an environment variable)

### Traditional Installation

```sh
pip install yival
```

### Install by Poetry

1. **Install [Poetry](https://python-poetry.org/docs/#installing-with-the-official-installer)**

2. **Clone Yival**

    ```sh
    git clone https://github.com/YiVal/YiVal.git
    cd Yival
    ```

3. **Initialize a Python virtual environment with `poetry`**

    ```sh
    poetry install --sync
    ```

## Demo

### Colab

| Demo | Supported Features | Colab Link |
|------|--------------------|------------|
| 🐯  Craft your AI story with ChatGPT and MidJourney| **Multi-modal** support of text and images.| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DgtDZghleiLEaaNF7f4vSGJ4ChDVls2X?usp=sharing) |
| 🌟 Evaluate different LLM Model Performance With Your Own Q&A Test Dataset| Easy model **evaluation and comparison** against 100+ models, thanks to LiteLLM. It provides a benchmark of model performances tailored to **your customized use case or test data**.| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1cSjsEKNwDq8W4O2oeRI93vH-BhYH5JXj?usp=sharing) |
| 🔥 Startup Company Headline Generation Bot | Automate prompt **evolution**   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1EiWUL8rE_kfNLXVPowCWCh6hwHFagvs_?usp=sharing) |
| 🧳 Build Your Customized Travel Guide Bot | Automate prompt generation by retrieving the most related popular prompt from the **community**. e.g. [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1L7miRwTQSZfm5xOKBakWOG5bOumMynpv?usp=sharing) |
| 📖 Build a Cheaper Translator: Let GPT-4 Teach Llama2 to Create an Cheaper Translator| Use GPT-4-generated test data to **fine-tune** the translation bot of Llama2 with Replicate. 6% sacrifice in performance, 18x save in cost.| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1HtQOadV0o3vrXjVI9Nf0Xv4rLarqu-fv?usp=sharing) |
| 🤖️ Chat with Your Favorite Characters - 澹台烬 from《长月烬明》|Give your character a soul with automated prompt generation and **character scripts retrieval**| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12XS1fhgxRAHsRZPXtJ8c5exslgj7EDHE#scrollTo=31Wq1Oeb-bSY) |

### Multi-model Mode

Yival has multimodal capabilities and can handle generated images in AIGC really
well.

Find more information in the Animal story demo we provided.

```bash
yival run demo/configs/animal_story.yml
```

![pic](https://github.com/YiVal/YiVal/assets/55043304/553a2369-adcf-4fbd-a4dc-64e2ecba0e09)

### Basic Interactive Mode

To get started with a demo for basic interactive mode of YiVal, run the
following command:

```python
yival demo --auto_prompts
```

Once started, navigate to the following address in your web browser:

<http://127.0.0.1:8073/interactive>
<details>
  <summary>Click to view the screenshot</summary>
  
  ![Screenshot 2023-08-17 at 10 55 31 PM](https://github.com/YiVal/YiVal/assets/1544154/a720c3ad-1288-4830-8a3d-377d9827f46e)
  
</details>

For more details on this demo, check out the [Basic Interactive Mode Demo](https://github.com/YiVal/YiVal/blob/master/docs/docs/basic_interactive_mode.md#demo).

### Question Answering with expected result evaluator

```python
yival demo --qa_expected_results
```

Once started, navigate to the following address in your web browser:
<http://127.0.0.1:8073/>
<details>
  <summary>Click to view the screenshot</summary>
  
 <img width="1288" alt="Screenshot 2023-08-18 at 1 11 44 AM" src="https://github.com/YiVal/YiVal/assets/1544154/4e9a182f-07ba-413e-9160-f38bfdc743ce">

</details>

For more details, check out the [Question Answering with expected result evaluator](https://github.com/YiVal/YiVal/blob/master/docs/qa_expected_results.md#demo).

### Automatically generate prompts with evaluator

```python
yival demo --basic_interactive
```

Once started, navigate to the following address in your web browser:
<http://127.0.0.1:8073/>
<details>
  <summary>Click to view the screenshot</summary>
  
 <img width="1288" alt="Screenshot 2023-08-18 at 1 11 44 AM" src="https://github.com/YiVal/YiVal/assets/1544154/4e9a182f-07ba-413e-9160-f38bfdc743ce">

</details>

# Contributors

<p align="center">
🌟 YiVal welcomes your contributions! 🌟<p align="center">
🥳 Thanks so much to all of our amazing contributors 🥳</p>

</p>
<a href="https://github.com/YiVal/YiVal/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=YiVal/YiVal" />
</a>

## Paper / Algorithm Implementation

| **Paper** | **Author** | **Topics** | **YiVal Contributor** | **Data Generator** | **Variation Generator** | **Evaluator** | **Selector** | **Evolver** | **Config** |
|---|---|---|---|---|---|---|---|---|---|
| [Large Language Models Are Human-Level Prompt Engineers](https://arxiv.org/abs/2211.01910) | [Yongchao Zhou](https://arxiv.org/search/cs?searchtype=author&query=Zhou,+Y), [Andrei Ioan Muresanu](https://arxiv.org/search/cs?searchtype=author&query=Muresanu,+A+I), [Ziwen Han](https://arxiv.org/search/cs?searchtype=author&query=Han,+Z) | YiVal Evolver, Auto-Prompting | [@Tao Feng](https://github.com/oliverfeng) | [OpenAIPromptDataGenerator](https://github.com/YiVal/YiVal/blob/master/src/yival/data_generators/openai_prompt_data_generator.py) | [OpenAIPromptVariationGenerator](https://github.com/YiVal/YiVal/blob/master/src/yival/variation_generators/openai_prompt_based_variation_generator.py) | [OpenAIPromptEvaluator](https://github.com/YiVal/YiVal/blob/master/src/yival/evaluators/openai_prompt_based_evaluator.py), [OpenAIEloEvaluator](https://github.com/YiVal/YiVal/blob/master/src/yival/evaluators/openai_elo_evaluator.py) | [AHPSelector](https://github.com/YiVal/YiVal/blob/master/src/yival/result_selectors/ahp_selection.py) | [OpenAIPromptBasedCombinationImprover](https://github.com/YiVal/YiVal/blob/master/src/yival/combination_improvers/openai_prompt_based_combination_improver.py) | [config](https://github.com/YiVal/YiVal/blob/master/demo/configs/headline_generation_improve.yml) |
| [BERTScore: Evaluating Text Generation with BERT](https://arxiv.org/abs/1904.09675) | [Tianyi Zhang](https://arxiv.org/search/cs?searchtype=author&query=Zhang,+T), [Varsha Kishore](https://arxiv.org/search/cs?searchtype=author&query=Kishore,+V), [Felix Wu](https://arxiv.org/search/cs?searchtype=author&query=Wu,+F) | YiVal Evaluator, bertscore, rouge | [@crazycth](https://github.com/crazycth) | - | - | [BertScoreEvaluator](https://github.com/YiVal/YiVal/blob/master/src/yival/evaluators/bertscore_evaluator.py) | - | - | - |
| [AlpacaEval](https://github.com/tatsu-lab/alpaca_eval) | [Xuechen Li](https://arxiv.org/search/cs?searchtype=author&query=Xuechen%20Li), [Tianyi Zhang](https://arxiv.org/search/cs?searchtype=author&query=Tianyi%20Zhang), [Yann Dubois](https://arxiv.org/search/cs?searchtype=author&query=Yann%20Dubois) et. al | YiVal Evaluator | [@Tao Feng](https://github.com/oliverfeng) | - | - | [AlpacaEvalEvaluator](https://github.com/YiVal/YiVal/blob/master/src/yival/evaluators/alpaca_eval_evaluator.py) | - | - | [config](https://github.com/YiVal/YiVal/blob/master/demo/configs/alpaca_eval.yml) |
[Chain of Density](https://arxiv.org/pdf/2309.04269.pdf) | [Griffin Adams](https://arxiv.org/search/?query=Griffin+Adam) [Alexander R. Fabbri](https://arxiv.org/search/?query=Alexander+R.+Fabbri) et. el | Prompt Engineering |[@Tao Feng](https://github.com/oliverfeng) | | [ChainOfDensityGenerator](https://github.com/YiVal/YiVal/blob/master/src/yival/variation_generators/chain_of_density_prompt.py) | | | | [config](https://github.com/YiVal/YiVal/blob/master/demo/configs/summary_config.yml)
