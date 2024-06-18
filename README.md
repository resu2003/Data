# Earthquake Data VIsualization using Tableau & ReactJS

This project is a data visualization tool that utilizes the Tableau Public API v3 to embed sheets into a ReactJS webpage. The project focuses on analyzing seismic waves and activity patterns over time using the Earthquake Dataset. This analysis aims to reduce the destruction caused by future earthquakes.


## Pre-Requisites

1. **Node JS**: [Download Node JS](https://nodejs.org/en/about)
2. **NPM**: [Learn about NPM](https://docs.npmjs.com/about-npm)
3. **IDE**: Any IDE, preferably [VS Code](https://code.visualstudio.com/docs)
4. **Internet**: Required to load Tableau containers using [Tableau API](https://help.tableau.com/current/api/embedding_api/en-us/index.html)

## Installation
1. **Clone the Repository**:
   - The dataset for analysis is included in the repository.
   - Use the following command to clone the repository:
     ```sh
     git clone https://github.com/resu2003/Data-Visualization-using-Tableau-ReactJS.git
     cd repository
     ```
   - Note that the `node_modules` directory is excluded due to `.gitignore`, so it won't be included in the clone.

2. **Install Dependencies**:
   - To run the project locally, you'll need to install the required dependencies:
     ```sh
     npm install
     ```
   - Then start the project:
     ```sh
     npm start
     ```

3. **Alternative Setup**:
   - For a more error-free setup, create a new React project and replace its files with the ones from the repository:
     ```sh
     npx create-react-app your_project_name
     ```
   - Copy all the files from the cloned repository into this new project directory.

## Running the Project

- **Tableau Public Project**: [Earthquake Data Analysis](https://public.tableau.com/views/Ca-4FINAL/Dashboard1)

After you've successfully copied all the files, follow these steps to run the project:

1. **Open your IDE**:
   - Fire up any Integrated Development Environment (IDE) of your choice. VS Code is recommended for its built-in terminal.

2. **Navigate to the Project Directory**:
   - Open a separate terminal and use the `cd` command to navigate to the project directory. Alternatively, use the built-in terminal in VS Code.

3. **Install React Router Dom**:
   - Run the following command to install the `react-router-dom` package:
     ```sh
     npm install react-router-dom
     ```
   - Wait patiently for the package to finish installing.

4. **Start the Project**:
   - Kick off the project with this command:
     ```sh
     npm start
     ```
   - The project should automatically launch in your default browser. If it doesn't, simply open any browser and navigate to `http://localhost:3000/`.

## Project Structure

- **App.js**: Main home page component.
- **index.js**: Handles routing.
- **DvttDashboard.js & sheet(no:).js**: JavaScript files acting as containers for each Tableau sheet. Modify these to add custom Tableau public URLs.
- **CSS Files**: Edit inline and separate CSS files for styling.

## Outputs

![Screenshot 1](https://github.com/jubinjacob03/DvttViz_EQdataset-ReactJS/assets/118928433/023eca18-3f80-42fb-952e-1b9ee4d602f6)
![Screenshot 2](https://github.com/jubinjacob03/DvttViz_EQdataset-ReactJS/assets/118928433/2b242ae3-5849-44ae-b380-314dfb0d69fe)
![Screenshot 3](https://github.com/jubinjacob03/DvttViz_EQdataset-ReactJS/assets/118928433/7cd2515d-4892-42cd-b2da-d908748362a0)
![Screenshot 4](https://github.com/jubinjacob03/DvttViz_EQdataset-ReactJS/assets/118928433/39d87902-095c-4fb6-a63e-bd1d6833ea78)
![Screenshot 5](https://github.com/jubinjacob03/DvttViz_EQdataset-ReactJS/assets/118928433/a9d661a3-9c93-49a0-8811-275f4eef310f)

## Help and References

- **Tableau Public APIv3 Documentation**: [Read here](https://help.tableau.com/current/api/embedding_api/en-us/index.html)
- **React Router Dom Guide**: [Learn here](https://bobbyhadz.com/blog/react-onclick-redirect)

### Modifying the Project

1. **App.js**: Modify the main home page component.
2. **index.js**: Edit for routing configurations.
3. **DvttDashboard.js & sheet(no:).js**: Change URLs to embed your custom Tableau public visualizations.
4. **CSS Files**: Adjust styles in both inline and separate CSS files.

Keep the remaining files as they are unless you have a clear understanding of their roles.

---

Happy coding! If you have any questions or need further assistance, feel free to reach out.

