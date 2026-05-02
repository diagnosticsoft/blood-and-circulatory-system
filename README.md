## Human Blood and Circulatory System

A concise, educational documentation project covering the human blood and circulatory system. It explains the structure and function of blood components, the roles of plasma, red and white blood cells, and platelets, and how the heart and blood vessels work together to transport oxygen, nutrients, and immune defenses throughout the body.

### Getting started
1. **Clone the project**
   - ``git clone https://github.com/phattrienai/blood_circulatory_sys_documentation.git``
   - ``cd blood_circulatory_sys_documentation``
2. **Create a virtual environment and activate it**
   - ``python3 -m venv venv``
   - ``source venv/bin/activate`` (macOS / Linux)
   - ``venv\Scripts\activate.bat`` (Windows)
3. **Install dependencies**
   - ``pip install -r requirements.txt``
4. **Generate documentation**
   - ``make clean revealjs``
5. **Open the generated slides**
   - Open ``build/revealjs/index.html`` in a browser

### Deployment
The documentation can be deployed to GitHub Pages for easy access. To do this, follow these steps:
1. **Build the documentation**
   - ``make clean revealjs``
2. **Deploy to GitHub Pages**
   - ``gh-pages -d build/revealjs`` 

### Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.