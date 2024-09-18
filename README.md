# 🔣 Visual Compute


Welcome to Visual Compute, where creativity meets mathematical analysis! This innovative web application empowers users to express their artistic skills while seamlessly integrating mathematical problem-solving.With a user-friendly interface, you can easily create drawings on a full-screen canvas using a variety of colors. Simply sketch your mathematical expressions, submit them for processing, and watch as the results are rendered in elegant LaTeX format. 

## Features

- **Draw on Canvas**: Users can draw freely on a full-screen canvas.
- **Color Selection**: Choose from a palette of colors to customize drawing.
- **Calculate**: Submit the drawn image for mathematical processing.
- **LaTeX Rendering**: View results in a beautifully rendered LaTeX format.
- **Reset Canvas**: Clear the canvas with a confirmation prompt.
- **Loading Indicator**: Feedback during calculations.

## Technologies Used

- **React**: Frontend framework for building the user interface.
- **Backend**: FastAPI, Python
- **Axios**: For making API requests.
- **MathJax**: For rendering LaTeX mathematical expressions.
- **Mantine**: A React component library for UI elements.
- **Draggable**: For moving LaTeX results around the canvas.
- **Deployment**: Uvicorn for FastAPI server
## Installation
 Clone the repository:
   ```bash
   git clone https://github.com/yourusername/VisualCompute.git
```
**Frontend Setup**

1.Navigate to the frontend directory :
   ```bash
  cd Frontend
```
2.Install frontend dependencies:
   ```bash
 npm install
 npm i react-router-dom axios
 npm i mathjax @type/mathjax
 npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```
3.Install Shadcn library:
  ```bash
 npx  shadcn@latest init 
 npx shadcn@latest add button
```

4.Create the .env file:
   ```bash
VITE_API_URL="your local host"
```
5.Start the server:
   ```bash
  npm run dev
```

**Backend Setup**

1.Navigate to  Backend Directory:
```
cd Backend
```
2.Create and activate a virtual environment:
```
python -m venv venv
source venv/bin/activate 

```
3.Install backend dependencies:
```
pip install fastapi pillow unicorn pydantic googlegenerativeai python-dotenv

```
4.Create a constants.py file in the /constants directory:
```SERVER_URL='localhost'
PORT='8900'
ENV='dev'
GEMINI_API_KEY=os.getenv("GEMINI_API_KEY'")
```
5.Create the .env file:
```
GEMINI_API_KEY="generate your api key"
```
6.Run the FastAPI server:
```
python3 main.py

```


