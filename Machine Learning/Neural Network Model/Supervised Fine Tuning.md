Supervised Fine Tuning allows a model to adapt to specific tasks or datasets and improving its performance on those tasks by changing model parameters ..

The model's parameters are adjusted to minimize the difference between the model's predictions and the actual values in the smaller dataset

-> in supervised fine tunning its better to fine tune a  chat mode, and only train it on a specific topic

## Approachs
1. choosing the fine tuning task --> text generation, classification..
2. preparing the datasets --> "which expected to be some questions and answers related to our topic...
	- "prompt":------------
	- "completion": ---------------   " 
3. choose the base model --> "arabert"
4. fine tune the model using the supervised approach -->"[[parameters training methods]]"  
5. evaluate the performance 

------------------------------------------
Attention (0,1):
هي حاجة بتقول للموديل يشوف الكلمات الي قبلها عشان يعمل توقع على اساسها ولا لا

Loss mask (0,1):
زي كانه بيقول للموديل اعمل توقع للكلمة الي بعدها ولا لا؟
و بعد كده بناءا على توقعه بنشوف هو كويس ولا لا و ع اساسه بنشوف عايز يعمل اي تعديلات ع التوقع الي عمله ولا لا

----------------------------------------------
in supervised we make an attention on the questions, but there is no need to make a loss mask on the question, because here we are focusing on training the model on predicting the answer and increasing the answer's performance
-> focusing also on the end token, which telling the model where to stop predicting...

## Links
- [What is supervised fine-tuning? — Klu](https://klu.ai/glossary/supervised-fine-tuning)
- [Embeddings vs Fine Tuning - Part 2, Supervised Fine-tuning - YouTube](https://www.youtube.com/watch?v=DMcxxg5iEZQ&ab_channel=TrelisResearch)
- [Lecture 8: How ChatGPT Works Part 1 - Supervised Fine-Tuning - YouTube](https://www.youtube.com/watch?v=3xV_nNl6DCI&ab_channel=AiCore)
### preparing Datasets from raw text:
- [How To Create Datasets for Finetuning From Multiple Sources! Improving Finetunes With Embeddings. - YouTube](https://www.youtube.com/watch?v=fYyZiRi6yNE&ab_channel=AemonAlgiz)
- [GitHub - Aemon-Algiz/DatesetExtraction: Example code for extracting Q&A datasets from LLM's](https://github.com/Aemon-Algiz/DatesetExtraction/tree/main)
- [Prepare Fine-tuning Datasets with Open Source LLMs - YouTube](https://www.youtube.com/watch?v=JJ5mcdEIbj8&ab_channel=TrelisResearch)



