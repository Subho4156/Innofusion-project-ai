# nirnayaak

Blog link: https://soumyajitdatta.hashnode.dev/introducing-nirnayaak-the-ai-behind-revolutionary-web-application-simplifying-legal-research

nirnayaak is a web application that allows users to search for legal cases using keywords and view the results in a user-friendly manner. This is the backend repository for the project. Hosted in AWS at ml-backend.nirnayaak.co

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

`pip install -r requirements.txt`

and then, to run the server:

`python app.py`


## Key Features
* Search for cases using keywords
* Upload PDFs of cases
* Authorization and Authentication
* Get Keywords for auto-complete
* Sorting algorithm for search results
* Authorization using AES Encryption

## Key Technologies and Libraries Used
* Python
* Flask
* MongoDB
* Pytessaract
* pdf2image
* Spacy
* TextBlob
* NLTK
* YAKE
* PIL
* wordfreq
* AWS S3 Bucket
* AWS EC2 instance

## Postman API Documentation

[Postman API Documentation]()
## Preprocessing and Keyword Extraction Procedure

Keyword Extraction is done using unsupervised ML algo called Yet Another Ranking Algorithm(YAKE). The keywords are then stored in the database along with the case.

![Keyword Extraction Procedure](https://res.cloudinary.com/dfediigxy/image/upload/v1677389434/Untitled_Diagram.drawio-8_npeyyb.png)
