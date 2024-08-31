# Plant Disease Identification Using Deep Learning

## Overview
This project implements a deep learning model to identify diseases in plant leaves using image recognition. It provides a web interface for users to upload images of plant leaves and receive predictions about potential diseases.

## Features
- Image upload functionality
- Real-time disease prediction
- Supports identification of multiple plant diseases
- User-friendly web interface
- Responsive design for various devices

## Technologies Used
- Python
- TensorFlow / Keras for deep learning
- Flask for web server
- HTML/CSS/JavaScript for frontend
- Bootstrap for responsive design

## Setup and Installation

### Prerequisites
- Python 3.7+
- pip (Python package manager)

### Steps
1. Clone the repository:
   ```
   git clone https://github.com/Git-me-Harish/Plant-Disease-Identification.git
   cd Plant-Disease-Identification
   ```

2. Create and activate a virtual environment:
   ```
   python -m venv myenv
   source myenv/bin/activate  # On Windows, use: myenv\Scripts\activate
   ```

3. Install required packages:
   ```
   pip install -r requirements.txt
   ```

4. Download the pre-trained model file `Plant.keras` (not included in the repository due to size constraints) and place it in the project root directory.

## Usage

1. Start the Flask server:
   ```
   python app.py
   ```

2. Open a web browser and navigate to `http://localhost:5000`

3. Upload an image of a plant leaf through the web interface

4. The system will process the image and display the predicted disease (if any)

## Model Information
The deep learning model used in this project is trained on a dataset of various plant leaf images. It can identify several common plant diseases across different plant species.

## Project Structure
- `app.py`: Main Flask application
- `templates/`: HTML templates for the web interface
- `static/`: CSS, JavaScript, and image files
- `Plant.keras`: Pre-trained Keras model (not included in repository)
- `requirements.txt`: List of Python dependencies

## Contributing
Contributions to improve the project are welcome. Please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes and commit (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## License
[MIT License](https://opensource.org/licenses/MIT)

## Contact
For any queries or suggestions, please open an issue on the GitHub repository.

---

Remember to keep your model updated and expand the dataset to improve accuracy over time. Happy plant disease identifying!
