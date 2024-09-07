File Finder API
This repository contains a REST API that enables you to search for files on your computer. The API provides two main functionalities:

Features
1. Search Entire Computer for a File
You can search the entire computer for a specific file by providing the filename as a parameter. The API will traverse the entire system to locate the file.

Example Request:

GET localhost:8080/findMyFile?fileName=Errors-Solutions.txt

2. Search Within a Specific Folder
If you want to search within a specific folder, you can specify both the filename and the folder path in the URL. This allows for a more targeted search.

Example Request:

GET localhost:8080/searchInFolderFile?fileName=.pdf&searchInFolder=C%3A%5CGames


Getting Started

Prerequisites
Java 17
Gradle
Installation
Clone the repository and navigate into the project directory:


git clone https://github.com/yourusername/FileFinderAPI.git
cd FileFinderAPI
Running the Application
You can run the application using Maven or Gradle.

For Maven:
mvn spring-boot:run

For Gradle:
./gradlew bootRun

The application will start on http://localhost:8080.

Usage
Use the API endpoints to search for files on your computer as described in the Features section.
