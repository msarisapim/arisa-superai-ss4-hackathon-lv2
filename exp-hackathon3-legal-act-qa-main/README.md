# Hackathon3-legal-act-qa



## Getting started

To make it easy for you, i will provide some guidelines and a bit explanation for each code.

## Concept
Our group decided to use classical model for solving this task.
Extratree Classifier was chosen because tree base algorithm is suitable for the logical task. Also, it's tree with ensembled in itself.

## Step
1. We just use raw data and embeded it as you can see in (Embedding_of_Legal_Act_Hack_Ensemble2.ipynb) file.
2. Then, we use Extratree Classifier. (ULT_ah_oau.ipynb) 
3. We also tried fushion way. (Lexicalsemantic_catboost_fusion.ipynb)
4. Lastly, we did some rule-base. (compare.ipynb)

## Detail (in Thai)
ถ้าให้เล่าหลักการคร่าวๆ คือการที่เอา data มา embed เพื่อแปลง text to vector เพราะว่า จริงๆแล้วพอเรา deal กับ ตัวเลขได้ มันค่อนข้างที่จะง่ายต่อการนำไปใช้ บวกกับอีกกลุ่มทำสาย transformers เราเลยอยากลองสาย classical จริงๆมันก็มีอีกทางเลือกที่เราสามารถทำได้คือ LLM แต่ LLM พวกเรารู้สึกว่ามันค่อนข้างจะจับฉ่าย มันใช้แก้ปัญหาทุกอย่างเกินไป เราเลยอยากลองอะไรที่ท้าทาย ซึ่งเราก็ได้ผลลัพธ์ที่เกินคาดเลย เพราะว่าคะแนนเราเกือบจะสู้คนที่ทำ transformers ได้
