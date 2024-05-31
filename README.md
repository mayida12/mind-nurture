# 🌿 Mind Nurture

Welcome to **Mind Nurture** – your digital companion for mental health support and personal growth.

## 📝 Description
Mental health issues affect millions worldwide, often leading to untreated conditions due to stigma, fear, or lack of access to care. **Mind Nurture** aims to bridge this gap by providing essential information and support through various features designed to nurture your mental well-being.

### Key Features
- **💬 Health Chatbot**: Leveraging the LLama-2 model, fine-tuned with the Hugging Face dataset, our chatbot offers personalized health advice based on user inputs. [Hugging Face Dataset](https://huggingface.co/datasets/vibhorag101/phr_mental_therapy_dataset)
- **🔐 Login/Signup**: Secure user authentication to access the website's features.
- **👤 Profile**: Users can view and update their profile details, including name, age, gender, and personal reviews.
- **📓 Journaling**: A React-based digital journal for recording thoughts, feelings, and experiences, promoting emotional processing and tracking mental health progress.
- **📊 Habit Tracking**: Custom habit tracking for activities like exercise, meditation, medication adherence, sleep patterns, and social interactions.
- **📖 Personal Stories**: Inspiring real-life narratives and testimonials from individuals who have faced mental health challenges and shared their recovery journeys.

## 🔗 Links
- [GitHub Repository](https://github.com/mayida12/mind-nurture)


## 🤖 Tech Stack
**Front-end**:
- HTML
- CSS
- Bootstrap
- JavaScript
- ReactJS

**Back-end**:
- ReactJS
- ExpressJS
- Mongoose
- Python
- Flask
- Flask_ngrok
- Ngrok

**Database**:
- MongoDB

**Natural Language Processing**:
- Transformers
- Accelerate
- PEFT
- Bitsandbytes
- Torch
- Langchain

## 📈 Progress
- 💬 Chatbot
- 🔐 Login/Signup and Logout functionality
- 📓 Journaling with update and delete functionality
- 👤 Profile page displaying biodata
- 📈 Fetch data using API
- 📝 Personality Test
- 📖 Personal Stories

## 🔮 Future Scope
- Locating nearby professional healthcare providers
- Middleware connection to therapists

## 💸 Applications
**Mind Nurture** combines multiple functionalities into a user-friendly platform with a wellness-focused chatbot, providing both support and connection opportunities.

## 🛠 Project Setup
### Clone the Repository:
Open a terminal window and run:
```bash
git clone https://github.com/mayida12/mind-nurture.git
```

### Navigate to the Project Directory:
```bash
cd mind-nurture
```

### Install Frontend Dependencies:
Navigate to the client directory and install dependencies:
```bash
cd client
npm install
```

### Install Backend Dependencies:
Navigate back to the project root and then to the server directory to install dependencies:
```bash
cd ..
cd server
npm install
```

## 💻 Usage
### Running the Application
1. **Open Two Terminal Windows**:
   - For Windows: Press `Windows + R`, type `cmd`, and press Enter.
   - For macOS/Linux: Open your preferred terminal application.

2. **Navigate to the Project Directory** in both terminals:
   ```bash
   cd path/to/mind-nurture
   ```

3. **Run the Frontend**:
   In one terminal, navigate to the client directory and start the development server:
   ```bash
   cd client
   npm start
   ```

4. **Run the Backend**:
   In the other terminal, navigate to the server directory and start the backend server:
   ```bash
   cd server
   npm run devStart
   ```

### For the Chatbot
- **If you have a GPU**, ensure you have CUDA installed, then run `app.py`.
- Alternatively, run `server.ipynb` on Colab. After running, replace the link in `client/src/bot/ActionProvider.jsx` line 12 with the provided output link.

### Access the Web App:
Open a web browser and navigate to `http://localhost:3000`.

**Additional Notes**:
- The frontend app will automatically reload with code changes.
- Console messages will appear in both terminal windows during development.
- Stop the servers with `Ctrl+C` when done to free up resources.

## 👨‍💻 Team Members
- Mayida
- Rishita Sharma
- Suhani Koul
- Priyanka Razdan
