# ViT_Eperiments

This colab notebook gives a quick look into Visual Transformers tasks using pre-trained models. It uses the Transformers library by Hugging Face.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ajishpradeep/ViT_Eperiments/blob/main/HuggingFace_ViT_Experiment.ipynb)

# Projects
### 1. Visual Question Answering 
### 2. Depth Estimation



## Prerequisites

- Python 3.x
- `pip` package manager
- `transformers` package
- `validators` package

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Install the required packages:

```bash
pip install transformers
pip install validators
```

## Usage

1. Run the script:

```bash
python image_analysis.py
```

2. Enter the image URL when prompted. It can be a URL of an image on the web or a local file path.

#### Example
```bash
Enter the Image URL: http://example.com/image.jpg
Image is from the web
```

3. The script will display the image and prompt you to enter a question.

4. After entering the question, the script will perform visual question answering using the VILT model and display the answer.

#### Example
```bash
Your Question: What is in the image?
[{'answer': 'cat', 'score': 0.987}]
```

5. It will then estimate the depth of the image using the DPT model and display the depth map.
