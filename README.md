# ChatStat 💬 📲 📈

ChatStat is a Streamlit web application that allows you to analyze your WhatsApp chat data. It provides insights such as message statistics, word clouds, emoji analysis, and more.

## Live Demo

You can access a live demo of the ChatStat app [Click here](https://chatstat-akash.streamlit.app/#6024).

## Installation

To run the application locally, you'll need Python 3.6+ installed. 

1. **Clone the repository and install the dependencies using pip**:

    ```sh
    git clone https://github.com/your-username/ChatStat.git
    cd ChatStat
    pip install -r requirements.txt

2. **Run the Streamlit app using the following command**:
    ```sh
    streamlit run app.py

## File Structure
- **app.py**: Main Streamlit application file.
- **preprocessor.py**: Preprocessing functions for WhatsApp chat data.
- **helper.py**: Helper functions for data analysis.
- **setup.sh**: Streamlit configuration file.
- **requirements.txt**: Python dependencies.
- **Procfile**: Heroku deployment configuration (not used for Streamlit Community Cloud).

## Deployments
This app can be deployed using the Streamlit Community Cloud. Push your code to a GitHub repository and deploy from there. For detailed instructions, refer to the Streamlit Sharing documentation.

## How It Works
Upload your WhatsApp chat export text file.
Select a user or group member for analysis.
Click "Show Analysis" to see various statistics and visualizations.


## Output Screen

![Output Screen](https://drive.google.com/uc?id=1PtKSiwWoLr2hnjigFfCze-x2_5GqsVAJ)
![Output Screen](https://drive.google.com/uc?id=1VVjK7sQBnCFdT4d5N4kF0hVOzc58VFSJ)
![Output Screen](https://drive.google.com/uc?id=1840WwdmFGp98ssa79orlMuLyYCodm-S9)


## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements.

## Acknowledgments
- Special thanks to the creators of Streamlit and the data visualization libraries used in this project.
