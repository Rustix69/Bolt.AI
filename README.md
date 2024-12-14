# Website Builder with Node.js, React, and Integrated LLM

## Overview
This project is a web application built using **Node.js** and **React** that leverages a **Large Language Model (LLM)** to enable users to generate and create websites effortlessly. The integrated LLM serves as a powerful assistant, guiding users through the website creation process and even generating code snippets and templates.

## Features
- **Dynamic Website Creation:** Users can create fully functional websites by interacting with the LLM.
- **LLM Integration:** The application utilizes an LLM to understand user inputs and generate website components, such as HTML, CSS, and JavaScript.
- **Modern Tech Stack:** Built with Node.js on the backend and React on the frontend for a seamless user experience.
- **Customizable Outputs:** Users can customize generated websites according to their needs.

## Tech Stack
### Frontend:
- **React**: A JavaScript library for building user interfaces.
- **CSS**: Styling for the application.
- **Axios**: For API requests to the backend.

### Backend:
- **Node.js**: A JavaScript runtime for building the server-side logic.
- **Express.js**: A web application framework for Node.js.
- **LLM API**: Integrated API for accessing the Large Language Model.

### Additional Tools:
- **Webpack**: Module bundler for React.
- **Babel**: JavaScript compiler.
- **MongoDB** (optional): For storing user data or generated website templates.

## Setup and Installation

### Prerequisites:
- Node.js installed on your system.
- API key for the LLM service.

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/Rustix69/Bolt.AI.git
   cd Bolt.AI
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up the environment variables:
   Create a `.env` file in the root directory and add the following:
   ```env
   LLM_API_KEY=your_api_key_here
   PORT=3000
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Access the application at `http://localhost:3000`.

## Screenshots: 
![image](https://github.com/user-attachments/assets/b602077a-9644-4f19-b1a7-bf5c6ee08726)


## How It Works
1. The user interacts with the React-based frontend to specify requirements for the website.
2. The frontend sends the user’s input to the backend via an API call.
3. The Node.js backend communicates with the LLM API to process the input and generate appropriate code snippets or templates.
4. The generated code is sent back to the frontend, where users can preview and download it.

## Future Enhancements
- Add support for more advanced website customization options.
- Include additional LLM models for diverse outputs.
- Provide hosting options for users to directly deploy their created websites.
- Enable multi-language support for global accessibility.
