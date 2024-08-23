### Flask OpenCV Streaming

This is a simple Flask server that streams video from your webcam using OpenCV. It uses the `VideoCapture` class from OpenCV to capture the video stream and then sends the frames to the client using Flask's `Response` class. The client then displays the video stream using React and the `img` tag.

### Installation

**Backend**
1. Clone the repository
2. Go to the backend directory
```bash
cd backend
```
3. Create a virtual environment
```bash
python -m venv venv
```
4. Activate the virtual environment
```bash
source venv/bin/activate
```
5. Install the requirements
```bash
pip install -r requirements.txt
```
6. Run the server
```bash
python app.py
```

**Frontend**
1. Go to the frontend directory
```bash
cd frontend
```
2. Install the dependencies
```bash
npm install
```
3. Run the development server
```bash
npm run dev
```

### Usage

Open your browser and go to `http://localhost:5000` to see the video stream.