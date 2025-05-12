# MyRealProduct - Build Products; Not Just Projects

Welcome to **MyRealProduct Workshop**! Whether you are a beginner or looking to level up your skills, these workshops will guide you through essential topics, tools, and hands-on guidance to help you build a solid profile. 

## 📅 Upcoming Cohort

We also feature **mentors** from the industry to share their experiences and insights!

| **Session**                    | **Start Date**             | **Location**             | **Join Link**       |
|---------------------------------|----------------------|--------------------------|---------------------|
| Summer Cohort  | May 31, 2025           | Online (Virtual Breakout Rooms)            | [Join Here](https://myrealproduct.com/)      |

---

### 🚀 **[Register for MyRealProduct Workshop Here](https://myrealproduct.com/)**

---

<div align="center">
	<p>
		<a href="https://myrealproduct.com/">
			<b>Join MyRealProduct Workshop!</b>
			<br>
			Build Products; Not Just Projects. Live Workshop!
			<br>
			<div>
				<a href="https://myrealproduct.com/">
					<img src="https://myrealproduct.com/wp-content/uploads/2024/06/cropped-Yellow-and-Green-Modern-Logo.png" width="300" alt="MyRealProduct Logo">
				</a>
			</div>
		</a>
		<sub><i>Join our community and get hands-on with building real product from scratch</i></sub>
	</p>
</div>

---
# Resume Roast - AI Edition 🔥

A fun web application that uses Google's Gemini AI to roast your resume in a humorous, sarcastic way. Upload your resume and get ready for some brutal honesty wrapped in comedy!

<p align="center">
   <img src="assets/Resume Roast Demo.gif" width="500">
</p>

## Features 🌟

- User authentication with secure password hashing
- Support for PDF and TXT resume uploads
- AI-powered resume roasting using Google's Gemini model
- Simple and intuitive web interface
- Secure storage of user credentials in AWS S3

## Prerequisites 📋

- Python 3.8 or higher
- A Google API key for Gemini AI
- AWS account with S3 access
- Internet connection

## Setup Instructions 🚀

1. **Clone the repository**
   ```bash
   git clone https://github.com/hariPrasadCoder/resume-roast-app.git
   cd resume-roast-app
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Get your Google API Key**
   - Visit the [Google AI Studio](https://aistudio.google.com/apikey)
   - Sign in with your Google account
   - Create a new API key
   - Copy the API key

6. **Set up AWS S3**
   - Create an S3 bucket in your AWS account
   - Create an IAM user with S3 access
   - Note down the AWS access key ID and secret access key

7. **Set up environment variables**
   - Create a `.env` file in the project root
   - Add your API keys and configuration:
     ```
     GEMINI_API_KEY=your_gemini_api_key_here
     AWS_ACCESS_KEY_ID=your_aws_access_key_id
     AWS_SECRET_ACCESS_KEY=your_aws_secret_access_key
     AWS_REGION=your_aws_region
     S3_BUCKET_NAME=your_s3_bucket_name
     ```

## AWS EC2 Setup Guide 🚀
You can find [AWS EC2 Setup Guide](./AWS_setup.md) here.


## Running the Application Locally

1. **Ensure your virtual environment is activated**

2. **Start the Streamlit server**
   ```bash
   python -m streamlit run main.py
   ```

3. **Access the application**
   - Open your web browser
   - Navigate to `http://localhost:8501`

## Usage Guide 📖

1. **First-time users**
   - Click the "Signup" button in the sidebar
   - Create your username and password
   - Login with your credentials

2. **Returning users**
   - Enter your username and password
   - Click "Login"

3. **Getting your resume roasted**
   - Upload your resume (PDF or TXT format)
   - Click "Roast my resume"
   - Wait for the AI to generate its humorous critique
   - Enjoy the roast! 🔥

## Security Notes 🔒

- Passwords are securely hashed using SHA-256
- Never share your API key
- Keep your `.env` file private

## Troubleshooting 🔧

- If you get API errors, verify your API key in the `.env` file
- Make sure all dependencies are installed correctly
- Check if your resume file is in PDF or TXT format
- Ensure you have a stable internet connection

## Contributing 🤝

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License 📄

[MIT License](LICENSE)

## Acknowledgments 👏

- Google Gemini AI for the roasting capabilities
- Streamlit for the awesome web framework
- All contributors and users of this project
