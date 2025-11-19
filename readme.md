# 📄 ACL Anthology Publication 
-** Anthology ID: 2025.ltedi-1.20**
### **Team_Luminaries_0227@LT-EDI-2025: A Transformer-Based Fusion Approach to Misogyny Detection in Chinese Memes**

🔗 **Anthology Link:** https://aclanthology.org/2025.ltedi-1.20/ <br>
🔗 **PDF:** https://aclanthology.org/2025.ltedi-1.20.pdf  

## 📝 Abstract  
Detecting misogyny in **Chinese memes** is especially challenging due to linguistic complexity, cultural nuance, and multimodal content (image + text).000 In the **LT-EDI@LDK 2025 Shared Task on Misogyny Meme Detection**, we explored both textual and visual features:

### 🧠 Text Models  
- **Chinese BERT** — *Best performer, F1: 0.86*  
- XLM-RoBERTa  
- DistilBERT  

### 🖼️ Image Models  
- **VGG16** — *Best performer, F1: 0.85*  
- ResNet  
- ViT  

### 🔥 Multimodal Fusion Result  
Combining **Chinese BERT + VGG16** produced the strongest results:
- **Macro F1 Score:** **0.90355**  
- **Rank:** **3rd place** in the competition  
Our multimodal fusion model effectively captured subtle visual–textual cues in Chinese memes, making significant improvements in misogyny detection.

## 🔖 Publication Details  
- **Conference:** 5th Conference on Language, Data and Knowledge (LDK 2025)  
- **Workshop:** Language Technology for Equality, Diversity, and Inclusion (LT-EDI)  
- **Location:** Naples, Italy  
- **Month:** September  
- **Year:** 2025  
- **Pages:** 116–120  
- **Publisher:** Unior Press  

## 👥 Authors
- **Adnan Faisal**  
- **Shiti Chowdhury**  
- **Momtazul Arefin Labib**  
- **Hasan Murad**

## 📌 ACL Citation
```bibtex
@inproceedings{faisal-etal-2025-team-luminaries,
    title = "{T}eam{\_}{L}uminaries{\_}0227@{LT}-{EDI}-2025: A Transformer-Based Fusion Approach to Misogyny Detection in {C}hinese Memes",
    author = "Faisal, Adnan  and
      Chowdhury, Shiti  and
      Labib, Momtazul Arefin  and
      Murad, Hasan",
    editor = "Gkirtzou, Katerina  and
      {\v{Z}}itnik, Slavko  and
      Gracia, Jorge  and
      Gromann, Dagmar  and
      di Buono, Maria Pia  and
      Monti, Johanna  and
      Ionov, Maxim",
    booktitle = "Proceedings of the 5th Conference on Language, Data and Knowledge: Fifth Workshop on Language Technology for Equality, Diversity, Inclusion",
    month = sep,
    year = "2025",
    address = "Naples, Italy",
    publisher = "Unior Press",
    url = "https://aclanthology.org/2025.ltedi-1.20/",
    pages = "116--120",
    ISBN = "978-88-6719-334-9",
    abstract = "Memes, originally crafted for humor or cultural commentary, have evolved into powerful tools for spreading harmful content, particularly misogynistic ideologies. These memes sustain damaging gender stereotypes, further entrenching social inequality and encouraging toxic behavior across online platforms. While progress has been made in detecting harmful memes in English, identifying misogynistic content in Chinese remains challenging due to the language{'}s complexities and cultural subtleties. The multimodal nature of memes, combining text and images, adds to the detection difficulty. In the LT-EDI@LDK 2025 Shared Task on Misogyny Meme Detection, we have focused on analyzing both text and image elements to identify misogynistic content in Chinese memes. For text-based models, we have experimented with Chinese BERT, XLM-RoBERTa and DistilBERT, with Chinese BERT yielding the highest performance, achieving an F1 score of 0.86. In terms of image models, VGG16 outperformed ResNet and ViT, also achieving an F1 score of 0.85. Among all model combinations, the integration of Chinese BERT with VGG16 emerged as the most impactful, delivering superior performance, highlighting the benefit of a multimodal approach. By exploiting these two modalities, our model has effectively captured the subtle details present in memes, improving its ability to accurately detect misogynistic content. This approach has resulted in a macro F1 score of 0.90355, securing 3rd rank in the task."
}



