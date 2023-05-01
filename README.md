# todolist-v1
# ToDoList Website

This repository contains the code for a simple todo list website that allows users to create new pages for different works by typing name in the URL and creates a different list. The website was built using HTML, CSS, Node.js, Express, and MongoDB.

## Installation

To run this project on your local machine, you need to follow these steps:

1. Clone the repository by running the following command in your terminal: 

    `git clone https://github.com/<your-github-username>/todolist-website.git`

2. Change the directory to the project directory using the following command:

    `cd todolist-website`

3. Install the dependencies by running the following command:

    `npm install`

4. Create a `.env` file in the root directory of the project and set the environment variables according to your own configuration. The following variables are required:

    ```
    MONGODB_URI=<your-mongodb-uri>
    PORT=<your-server-port>
    ```

5. Start the server by running the following command:

    `npm start`

6. Open your web browser and navigate to `http://localhost:<your-server-port>` to view the website.

## Usage

The website allows users to view existing todo lists, as well as create new ones. To create a new list, simply add a new item to the URL with the name of your choice. For example, to create a new list called "Work", simply navigate to `http://localhost:<your-server-port>/work`.

Once you have created a new list, you can add items to the list by typing them into the input field and clicking the "Add" button. To mark an item as completed, simply click the checkbox next to the item. To delete an item, click the "X" button next to the item.

## Contributing

Contributions to this project are always welcome. If you find a bug or have a feature request, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.
