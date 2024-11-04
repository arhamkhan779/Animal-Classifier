# Animal Recognition System

## Demo Video

Watch the demo of the application here:  
[![Watch the demo](https://img.youtube.com/vi/3O3_P6fyK20/0.jpg)](https://youtu.be/3O3_P6fyK20)

## Overview

This project implements an animal recognition system using machine learning techniques with a graphical user interface built in Tkinter. Users can paste the path of an image, and the application will identify the animal depicted in the image, facilitating a fun and interactive way to learn about different animals.

## Project Structure

```
.
├── application
├── imageresizer
├── model
├── webscrapper
├── .gitignore
├── Animal.mp4
├── LICENSE
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.x
- pip
- [Anaconda](https://www.anaconda.com/products/distribution) (recommended for package management)

### Required Libraries

To run this project, you will need to install the following libraries:

- TensorFlow
- OpenCV-Python
- Pillow
- NumPy

You can install these libraries using pip:

```bash
pip install tensorflow opencv-python pillow numpy
```

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/animal-recognition.git
   cd animal-recognition
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv env_name
   source env_name/bin/activate  # On Windows use `env_name\Scripts\activate`
   ```

3. **Install Required Libraries**:  
   Use the command provided above to install the required libraries.

### Running the Application

1. **Start the Tkinter Application**:
   Run the following command to start the Tkinter application:
   ```bash
   python application/app.py  # Adjust the path if necessary
   ```

## Workflow

1. **Data Ingestion**:
   - The application processes input images to prepare for animal recognition.

2. **Model Training**:
   - The trained model is developed and stored in the `model` directory. Ensure the model is properly loaded for predictions.

3. **Application Logic**:
   - The main application logic is handled in the `application` directory, allowing users to input the image path and receive predictions.

4. **User Interaction**:
   - Users can paste the image path in the Tkinter interface, and the application will display the predicted animal.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request to enhance the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the contributors and tools that facilitated the project, including libraries for machine learning and image processing.
