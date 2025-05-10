# Jing Design Portfolio

This is a personal portfolio website built with Flask, showcasing UI/UX and Product Design work.

## Setup Instructions

1. Create a virtual environment:
```bash
python -m venv venv
```

2. Activate the virtual environment:
- Windows:
```bash
venv\Scripts\activate
```
- macOS/Linux:
```bash
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python app.py
```

The website will be available at `http://localhost:5000`

## Project Structure

- `app.py`: Main Flask application file
- `templates/`: HTML templates
- `static/`: Static files (CSS, images, etc.)
- `requirements.txt`: Project dependencies

## Features

- Responsive design
- Project showcase
- About section
- Contact information
- Social media links 

<ul class="nav-links">
    <li><a href="{{ url_for('uxui') }}">UI/UX</a></li>
    <li><a href="{{ url_for('product') }}">Product Design</a></li>
    <li><a href="{{ url_for('about') }}">About Me</a></li>
    <li><a href="{{ url_for('contact') }}">Contact</a></li>
</ul> 