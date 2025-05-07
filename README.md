# MS-COCO-2014-Dataset-and-xmodal3600-captions-by-Google

# Tagalog Image Captioning Dataset


## 📁 Dataset Overview

- **Images**: A selected portion of the **MS COCO 2014 validation set**
- **Captions**: Each image has **five Tagalog captions**, professionally translated through the **Crossmodal project**
- **Language**: All captions are in **Tagalog (Filipino)**, designed for culturally and linguistically appropriate image descriptions

## 🔀 Data Split

To support model training and evaluation, the dataset is divided using an **80/10/10** ratio:

| Split      | Description                        | Percentage |
|------------|------------------------------------|------------|
| Training   | For model learning                 | 80%        |
| Validation | For tuning hyperparameters         | 10%        |
| Testing    | For final evaluation               | 10%        |

Each data point is stored in a JSONL file with the following format:

```json
{
  "image_id": "000000123456.jpg",
  "captions": [
    "Ang batang babae ay kumakain ng sorbetes.",
    "Isang bata ang nakaupo habang may hawak na sorbetes.",
    "Masayang kumakain ang bata sa parke.",
    "Ang sorbetes ay natutunaw habang kinakain ng bata.",
    "Isang eksena ng pagkabata at kasiyahan sa hapon."
  ]
}

