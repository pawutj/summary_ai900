## Describe features of Natural Language Processing (NLP) workloads on Azure

# Common NLP Tasks:
- Text Analysis - วิเคราะห์ความหมายของข้อความ
- Sentiment Analysis - วิเคราะห์อารมณ์/ความรู้สึก
- Language Translation - แปลภาษา
- Speech Recognition - แปลงเสียงเป็นข้อความ
- Text-to-Speech - แปลงข้อความเป็นเสียง
- Named Entity Recognition - ระบุชื่อเฉพาะ (คน, สถานที่, องค์กร)
- Key Phrase Extraction - ดึงวลีสำคัญ รวมถึงจัดหมวดหมู่
- Language Detection - ตรวจจับภาษา

## Azure Language Services
# Azure AI Language (Text Analytics)
- Feature ข้างบนที่ไม่ใช่แปลภาษา
# Azure AI Translator
แปลภาษา
- Custom Translation แปลพวกศัพท์เฉพาะ
- Conversation Translation realtime

## Azure AI Speech
- SST
- TTS
- Speech Translation
- Speaker Recognition
- Intent Recognition (คู่กับ  Language Understanding (LUIS))

# Language Understanding
- Intent Recognition (BookFlight, CancelOrder, GetWeather)
- Entity Extraction ดึงข้อมูลสำคัญจากประโยค

#  Conversational AI Platform
- QnA Maker (ปัจจุบันรวมใน Language Service)  - สร้าง knowledge base จาก FAQ
- Azure Bot Service (เชื่อมต่อกับ LUIS และ QnA Maker)
