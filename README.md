

### **FADOHS - Framework for Detection and Integration of Unstructured Data of Hate Speech on Facebook Using Sentiment Analysis**  

#### **Project Overview**  
FADOHS is a machine learning-based framework designed to detect and analyze hate speech within unstructured social media data, particularly on Facebook. The system leverages **Natural Language Processing (NLP)** techniques like **sentiment and emotion analysis** to identify harmful content and classify it efficiently.  

#### **Features**  
- **Hate Speech Detection**: Uses NLP and machine learning models to identify dehumanizing or harmful language.  
- **Sentiment & Emotion Analysis**: Analyzes the tone and intent behind detected hate speech.  
- **Dataset Processing & Clustering**: Organizes detected hate speech for better evaluation.  
- **Machine Learning Integration**: Improves classification accuracy compared to existing solutions.  
- **Graph Analysis**: Identifies influential pages spreading hate speech on Facebook.  

#### **Tech Stack**  
- **Programming Language**: Python (3.8+)  
- **Framework**: Django  
- **Frontend**: HTML, CSS, JavaScript  
- **Database**: MySQL  
- **Machine Learning**: Scikit-learn, TensorFlow  
- **NLP**: NLTK, SpaCy  

#### **Installation Guide**  
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/chintalapudipiyush/FADOHS.git
   cd FADOHS
   ```

2. **Set Up Virtual Environment (Optional but Recommended)**  
   ```sh
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**  
   ```sh
   pip install -r requirements.txt
   ```

4. **Set Up the Database**  
   ```sh
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Run the Project**  
   ```sh
   python manage.py runserver
   ```

6. **Access the Application**  
   Open **http://127.0.0.1:8000/** in your browser.  

#### **Usage**  
- **Admins** can manage datasets, train models, and view analysis results.  
- **Users** can register, log in, and predict sentiment/emotion from input text.  
- **The system** processes and classifies data in real time to detect hate speech.  

#### **Contributors**  
- **Ch. Piyush** (217R1A05L9)  
- **B. Ravi Teja** (217R1A05L0)  
- **T. Vinay** (217R1A05R1)  
- **Under the guidance of** Mr. K. Ranjith Reddy (Assistant Professor, CMR Technical Campus)  

