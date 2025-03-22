# MediTwin

MediTwin is an AI-powered health companion application that provides personalized medicine insights based on user health profiles. It analyzes medications in the context of a user's specific health conditions, allergies, and current medications to deliver custom recommendations and safety information.

## 📚 Project Overview

This application consists of:
- A Next.js frontend for user interaction
- A Flask backend API that integrates with external services
- Integration with Google's Gemini AI for personalized medicine analysis
- OpenFDA API integration for drug information

## 👨‍💻 Contributors

Girish Bhuteja
- 📧 [Email](mailto:girishbhuteja07@gmail.com@gmail.com)  
- 🔗 [LinkedIn](https://www.linkedin.com/in/girishbhuteja0744/)

Jiya Pandit
- 📧 [Email](mailto:Jiyapandit01@gmail.com)
- 🔗 [LinkedIn](https://www.linkedin.com/in/jiya-pandit01)

Rudra Patel
- 📧 [Email](mailto:patel.rudra@gmail.com)
- 🔗 [LinkedIn](https://www.linkedin.com/in/rudrahere21/)

Dheeraj Choudhary
- 📧 [Email](mailto:dheeraj3choudhary@gmail.com)
- 🔗 [LinkedIn](https://www.linkedin.com/in/dheeraj-choudhary/)

## 🎥 Presentation 
Watch the full demo here: [Presentation](https://prezi.com/view/Yz6cawqzLxhU9cKdCx3j/)

## 🚀 Features

- ✅ User profile creation and management
- ✅ Health condition and medication tracking
- ✅ Personalized medicine analysis
- ✅ Drug safety information tailored to individual health profiles

## 🛠️ Tech Stack

### 🎨 Frontend
- Next.js 15.2.1
- React 19.0.0
- Axios for API requests
- Responsive design with custom CSS

### 🔧 Backend
- Flask with Flask-CORS
- Google Generative AI (Gemini 1.5 Flash)
- OpenFDA API integration
- Python 3.x

## 📂 Project Structure

```
├── backend/
│   ├── app/
│   │   ├── __init__.py
│   │   ├── routes.py
│   │   └── services.py
│   ├── .env
│   ├── config.py
│   ├── requirements.txt
│   └── run.py
│
├── frontend/
│   ├── app/
│   │   ├── medicine-inquiry/
│   │   │   └── page.js
│   │   ├── profile/
│   │   │   └── page.js
│   │   ├── results/
│   │   │   └── page.js
│   │   ├── layout.js
│   │   └── page.js
│   ├── components/
│   │   ├── Form.jsx
│   │   ├── Form.module.css
│   │   ├── StepIndicator.jsx
│   │   └── StepIndicator.module.css
│   ├── styles/
│   │   └── globals.css
│   ├── package.json
│   └── package-lock.json
```

## ⚙️ Setup and Installation

### 🔙 Backend Setup

1. Navigate to the backend directory:
   ```
   cd backend
   ```

2. Create and activate a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Create a `.env` file with the following variables:
   ```
   GEMINI_API_KEY=your_gemini_api_key
   OPENFDA_API_KEY=your_openfda_api_key
   SECRET_KEY=your_secret_key
   FLASK_DEBUG=True
   ```

5. Run the Flask application:
   ```
   python run.py
   ```

### 🎭 Frontend Setup

1. Navigate to the frontend directory:
   ```
   cd frontend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Run the development server:
   ```
   npm run dev
   ```

4. Access the application at `http://localhost:3000`

## 🔄 User Flow

1. User creates an account with basic information
2. User completes a health profile with conditions, allergies, and medications
3. User submits medication inquiries
4. System analyzes the medication against user's health profile
5. User receives personalized analysis results

## 📡 API Endpoints

- `GET /` - API health check
- `POST /user_profile` - Save user health profile
- `POST /drug_analysis` - Analyze a medication for a specific user

## ✨ Sample Screens

- Welcome page

![image](https://github.com/user-attachments/assets/93c6480a-f71c-46cc-9b13-f1a5484d4588)


- Health Profile page

![image](https://github.com/user-attachments/assets/f114b79f-fa2c-4921-8db2-dfd04354e57c)


- Medicine Inquiry Page

![image](https://github.com/user-attachments/assets/d4aac1ca-78a5-4ece-8346-6d0563ea1a60)

- Result page

![image](https://github.com/user-attachments/assets/99b5e00a-9444-4941-a0b7-3c8192deb678)

- Architecture Diagram

  ![image](https://github.com/user-attachments/assets/3f891321-4e17-4ae7-8723-8b89dd644b9f)


## 🔮 Future Enhancements

- User authentication with secure login
- Medication scheduling and reminders
- Interaction detection between multiple medications
- Export and sharing of medication analysis reports
- Mobile application with push notifications

## 📜 License

This project is licensed under the MIT License.
