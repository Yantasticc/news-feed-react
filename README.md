# News Feeds React + Vite Application

This React application provides a simple and user-friendly interface for accessing news articles from various categories, including Entertainment, Sports, Technology, Business, Health, and Science. It leverages the News API, which is a reliable HTTP REST API that allows you to search and retrieve live articles from across the web.

![News Feeds Screenshot](screenshot.png)

## Features

- Browse news articles from multiple categories.
- Filter articles by category (Entertainment, Sports, Technology, Business, Health, and Science).
- Search for specific articles by keywords.
- View detailed information about each article, including its title, source, publication date, and a brief description.
- Access the full article by clicking on the link provided in the details.
- Stay updated with the latest news in your areas of interest.

## Getting Started

To run this React application locally, follow these steps:

1. **Clone the Repository:**
https://github.com/Yantasticc/news-feed-react

2. **Navigate to the Project Directory:**
cd news-feeds-react-app

3. **Install Dependencies:**
npm install

4. **Obtain a News API Key:**
- Visit the [News API website](https://newsapi.org/) to create an account and obtain your API key.

5. **Configure Your API Key:**
- Create a `.env` file in the project's root directory.
- Inside the `.env` file, add your News API key as follows:
  ```
  VITE_API_KEY = your-api-key
  ```

6. **Start the Development Server:**
npm start

7. **Open Your Browser:**
- The application will be available at [http://localhost:3000](http://localhost:3000).

## Usage

- Select a category from the navigation bar (e.g., Entertainment, Sports, Technology, Business, Health, Science).
- Browse through the articles in the selected category.
- Use the search bar to find articles related to specific keywords.
- Click on an article to view its details and access the full article via the provided link.

## Dependencies

This project relies on the following main technologies and libraries:

- React
- Axios (for making HTTP requests)
- Bootstrap (for styling and UI components)
- [News API](https://newsapi.org/)

## Contributing

We welcome contributions to improve this application. If you would like to contribute, please follow these steps:

1. Fork the repository on GitHub.
2. Clone your fork locally.
3. Create a new branch for your feature or bug fix.
4. Implement your changes and commit them.
5. Push your changes to your fork on GitHub.
6. Submit a pull request to the main repository.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- This project makes use of the News API for retrieving news articles. Special thanks to the creators of News API for providing a valuable service.

Enjoy staying up to date with the latest news in your favorite categories! If you have any questions or encounter issues, please feel free to open an issue on this GitHub repository.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR (Hot Module Replacement) and some ESLint rules.

## Official Plugins

Currently, two official plugins are available to enhance the development experience:

1. **[@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md)**
- This plugin uses [Babel](https://babeljs.io/) for Fast Refresh, enabling a seamless development experience when working with React in Vite.

2. **[@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc)**
- This alternative plugin utilizes [SWC](https://swc.rs/) for Fast Refresh, providing an alternative approach to improving the development process when using React in Vite.
