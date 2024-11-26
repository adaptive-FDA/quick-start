# adaptiveFDA : Quick start

[![Deploy Mkdocs website](https://github.com/adaptive-FDA/quick-start/actions/workflows/deploy.yml/badge.svg)](https://github.com/adaptive-FDA/quick-start/actions/workflows/deploy.yml)

This project is a fast and brief introduction to adaptiveFDA theory and package.

The doc created is deployed at [this location](https://adaptive-fda.github.io/quick-start/)

## Mkdocs 

### About MkDocs

MkDocs is a static site generator that's geared towards project documentation. Written in Python, MkDocs is designed to be simple and easy to use, making it an excellent choice for developers who want to create clean, readable documentation for their projects. It uses Markdown files to generate the content, which ensures that the documentation is both easy to write and maintain. MkDocs also supports various themes and plugins, allowing users to customize the look and feel of their documentation to suit their needs.

#### Search Plugin

The search plugin is an essential tool for any documentation site. It allows users to quickly find the information they need by searching through the content. This plugin is particularly useful for large documentation sites where navigating through numerous pages can be cumbersome. By integrating the search plugin, you can enhance the user experience significantly.

#### MkDocs-Material

MkDocs-Material is a popular theme for MkDocs that provides a modern, material design look to your documentation. It is highly customizable and comes with a variety of features such as a responsive layout, dark mode, and support for various extensions. MkDocs-Material is known for its clean and professional appearance, making it a favorite among developers who want their documentation to look polished and professional.

#### MkDocs-Redirects

The MkDocs-Redirects plugin is useful for managing URL changes in your documentation. If you need to move or rename pages, this plugin ensures that users who visit the old URLs are automatically redirected to the new locations. This is particularly helpful for maintaining consistency and avoiding broken links, ensuring a seamless experience for your users.

### Setting Up a Python Environment with MkDocs

To get started with MkDocs, you'll need to set up a Python environment. Here are the steps to do so:

1. **Install Python**: Ensure you have Python installed on your system. You can download it from the official [Python website](https://www.python.org/).

2. **Create a Virtual Environment**: It's a good practice to create a virtual environment to manage your project's dependencies. You can do this using the following commands:
   ```sh
   python -m venv myenv
   ```
   Replace `myenv` with the name you want to give to your virtual environment.

3. **Activate the Virtual Environment**:
   - On Windows:
     ```sh
     myenv\Scripts\activate
     ```
   - On macOS and Linux:
     ```sh
     source myenv/bin/activate
     ```

4. **Install MkDocs**: With the virtual environment activated, install MkDocs using pip:
   ```sh
   pip install mkdocs
   ```

5. **Install Plugins**: You can install popular plugins like the search plugin, MkDocs-Material theme, and MkDocs-Redirects using the following commands:
   ```sh
   pip install mkdocs-material mkdocs-redirects
   ```

6. **Serve the Documentation Locally**: Navigate to your project directory and serve the documentation locally to see it in action:
   ```sh
   mkdocs serve
   ```
   Open your browser and go to `http://127.0.0.1:8000/` to view your documentation.

## Contributions Welcome

We gladly accept contributions from the community and thank all contributors in advance for their efforts. If you would like to contribute, please fork the repository, make your changes, and submit a pull request with a clear description of your modifications. Your contributions, no matter how small, are valuable and appreciated.
