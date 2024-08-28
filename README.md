# Streamlit App for Diagnosis Distribution

## Overview
This Streamlit app provides a visual representation of the distribution of different diagnoses leading to patient admissions. It includes various charts and images to help users understand the prevalance of different conditions.

## Features
- **Diagnosis Distribution**: Displays images illustrating the distribution of diagnoses, highlighting the most common conditions leading to patient admissions.

## Installation
To run this Streamlit app, you'll need to have Python installed. You can install the required dependencies using pip. Follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/your-repository.git
    cd your-repository
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the app**:
    ```bash
    streamlit run app.py
    ```

# File Structure
- `app.py`: Main Streamlit application file.
- `analysis.ipynb`: Main Jupyter file with all the predictive analysis.

# Example Code

## Diagnosis Distribution Section
The following code snippet shows how to include multiple images in the "Diagnosis Distribution" section of the app:

```
elif options == "Diagnosis Distribution":
    st.header("Distribution of Diagnoses")
    st.write("""
    The images below display the distribution of different diagnoses,
    highlighting the most common conditions leading to patient admissions.
    """)

    # Display the first image
    image_diagnosis1 = Image.open('path/to/diagnosis_distribution1.png')
    st.image(image_diagnosis1, caption='Distribution of Diagnoses - Image 1')

    # Display the second image
    image_diagnosis2 = Image.open('path/to/diagnosis_distribution2.png')
    st.image(image_diagnosis2, caption='Distribution of Diagnoses - Image 2')

    # Add more images as needed
    # image_diagnosis3 = Image.open('path/to/diagnosis_distribution3.png')
    # st.image(image_diagnosis3, caption='Distribution of Diagnoses - Image 3')
```
