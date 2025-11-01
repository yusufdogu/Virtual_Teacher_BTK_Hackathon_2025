
# Virtual Teacher Platform

Imagine an ordinary university day. In today’s higher education system, lecturers often have to repeat the same theoretical content every semester, while students—expecting to learn from online resources during exam periods—tend to skip theoretical lectures and attend only practical sessions.


To dive deeper into the concept and inspiration behind this project, check out my detailed Medium article:  
👉 [Revolutionizing Education — A Way of Putting a Teacher’s Brain into a Computer](https://ydogu159.medium.com/revolutionizing-education-a-way-of-putting-a-teachers-brain-into-a-computer-db479d4cccfe)



To address this inefficiency, the Virtual Teacher Platform aims to provide students with theoretical course materials through an online system before class sessions, allowing them to study in advance.

This approach enables students to come to class prepared, making more time for:

Practical exercises and in-class discussions

Reducing the monotony of theoretical teaching for instructors

Allowing instructors to focus on research and student engagement

Encouraging innovative and interactive learning experiences

This model aligns with the flipped classroom methodology, which already has successful examples worldwide.

However, our Virtual Teacher Platform takes it a step further by integrating Gemini Large Language Model (LLM) capabilities into the process of delivering theoretical content.

🧠 How It Works

Gemini assists both instructors and students throughout the learning process:

🎥 Summarizes uploaded lecture videos and materials

❓ Generates example questions related to each lesson

💬 Answers student queries about confusing concepts in real time

🌐 Finds related research papers and materials across the web

As a result:

Instructors can upload lecture videos, PDFs, slides, and papers directly to the platform

Theoretical teaching workload is reduced

Students can study materials in-depth before class using LLM-assisted summaries and Q&A

<img width="1885" height="878" alt="Sanal Öğretmen Platformu_1" src="https://github.com/user-attachments/assets/854d760f-0d5a-4122-bf5b-7adc8dde2602" />

<img width="1845" height="871" alt="Sanal Öğretmen Platformu_5" src="https://github.com/user-attachments/assets/0882a951-48f4-4d53-9bad-4d2b65f2fc35" />

<img width="1810" height="761" alt="Sanal Öğretmen Platformu_4" src="https://github.com/user-attachments/assets/2ff9a02b-88de-41ef-9247-d2539f201292" />

<img width="1846" height="866" alt="Sanal Öğretmen Platformu_3" src="https://github.com/user-attachments/assets/3177dcb9-c2e9-427b-a6d6-b0c08eaabf85" />

<img width="1861" height="874" alt="Sanal Öğretmen Platformu_2" src="https://github.com/user-attachments/assets/f01bf82a-bc8d-4cca-aebc-7bdf3025a62f" />

## 🚀 Planned Improvements and Future Enhancements

📂 Material Upload Page

🗣️ Automatic Transcription using Whisper during upload

💾 Storage system for uploaded materials

🔐 User authentication (login system)

###


## 🧩 Technologies Used

**Frontend:** Next.js, TailwindCSS

**Backend:** FastAPI

**External APIs:** Gemini API, Google Custom Search API


## ⚙️ Setup and Installation

To run the project locally, obtain the required API keys from the following services: <br>
🔶 https://console.cloud.google.com/marketplace/product/google/customsearch.googleapis.com?inv=1&invt=Ab4yOA&project=gen-lang-client-0393105183 
<br>
🔶 https://programmablesearchengine.google.com/controlpanel/all 
<br>
🔶 https://aistudio.google.com/app/apikey <br>

1. Clone the Repository

```bash
  git clone https://github.com/sherechogaki/MerkutX.git
```

2. Frontend Setup
   
```bash
  cd MerkutX\frontend
  npm install
  npm run start
```

3. Backend Setup

```bash
  cd MerkutX/backend
  python -m venv venv
  .\venv\Scripts\activate
  pip install -r requirements.txt
```

4. Configure Environment

```bash
  copy env.example .env
```

fill the .env with your API keys (Gemini API, Google Custom Search API)

5. Run the Backend
   
```bash
  uvicorn main:app --reload
```

6. Access the Platform

```bash
  Visit http://localhost:3000/ in your browser.
```
