# Product Comparator (Demo)

## Overview
allows users to compare financial products by accessing data directly from unauthenticated APIs of registered Data Holders.

## Using the Product Comparator
The Data Standards Body offers a [live demo](https://consumerdatastandardsaustralia.github.io/product-comparator-demo/) of the Product Comparator, accessible online for immediate use without any setup. This instance enables users to:

- View a comprehensive list of registered Data Holder Brands and their public details, automatically sourced from the CDR Register and updated within the tool.
- Temporarily add Data Holder brands and their server URLs using the 'Add' button.
- Fetch product data from the unauthenticated CDR product APIs (PRD), health check status data from the Status APIs and scheduled outage data from the Outages APIs for testing and verification.
- Compare products openly offered to the market by the Data Holders, displayed on a user-friendly, responsive webpage.
- Access a detailed log of API calls and responses for debugging Data Holder implementations.

Additionally, you can set up a local instance of the Product Comparator demo for customised and extended use cases. For more information, refer to the **Local Setup and Customisation** section below.

## Local Setup and Customisation
### Prerequisites
Before you begin, ensure you have the following installed:

- Git, for cloning the repository.
- [Node.js](https://nodejs.org/en/) (v10 or higher).
- npm (Node Package Manager) - **included with Node.js installation**.
- [Yarn](https://yarnpkg.com/) (Optional but preferred) - Javascript package manager

### Installation
1. Create a fork of this repository. To do this, click the **Fork** button in the top right corner of the GitHub [repository home page](https://consumerdatastandardsaustralia.github.io/product-comparator-demo/).
    
2. After forking the repository, clone it to your local machine. You can do this by running the following command in your terminal or command prompt:
    ```shell
    git clone https://github.com/your-username/project-name.git
    ```
    Replace **`your-username`** with your GitHub username and **`project-name`** with the name of your repository.
    
3. Once the repository is cloned, navigate to the project directory by running:
    ```
    cd project-name
    ```
    Replace **`project-name`** with the name of the repository.
    
4. Finally, install all necessary dependencies by running the following command in the project directory:
    ```shell
    npm install
    ```
    Or, if you prefer using Yarn:
    ```shell
    yarn install
    ```
### Run
1. Start the development server locally by running the following command in the project directory:
    ```shell
    npm run start
    ```    
    Or, if you are using Yarn:
    ```shell
    yarn start
    ```
2. Open your web browser and navigate to http://localhost:3000 to access the CDR Product Comparator (Demo) application.

### Build
1. Customise the project as needed for your specific use case.
2. Run `npm run build` OR `yarn build` to build production release
