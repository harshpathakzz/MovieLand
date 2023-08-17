# Movie Poster Viewer using OMdb API

This is a simple web application built with React.js and Vite that allows you to search for movies using the OMdb API and displays their posters along with release years. It provides an easy way to explore and discover movie posters of your favorite films.

## Features

- Search for movies using the OMdb API.
- Display movie posters along with their release years.
- Responsive design for seamless viewing on different devices.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js: Make sure you have Node.js installed on your machine.
- Yarn: You should have Yarn package manager installed globally.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/movie-poster-viewer.git
   ```

2. Navigate to the project directory:

   ```bash
   cd movie-poster-viewer
   ```

3. Install the dependencies using Yarn:

   ```bash
   yarn install
   ```

## Usage

1. Obtain an OMdb API key:

   Visit the [OMdb website](http://www.omdbapi.com/) and sign up to obtain an API key.

2. Create a `.env` file in the root directory of the project and add your API key:

   ```plaintext
   VITE_OMDB_API_KEY=your_api_key_here
   ```

3. Start the development server:

   ```bash
   yarn dev
   ```

4. Open your web browser and navigate to `http://localhost:3000` to use the application.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -am 'Add some feature'`.
4. Push the changes to your fork: `git push origin feature/your-feature-name`.
5. Submit a pull request to the `main` branch of this repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- This project was inspired by the desire to create a simple and visually appealing way to explore movie posters.
- The OMdb API powers the movie data retrieval.

---

Enjoy exploring movie posters with ease! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or contribute to the project. Happy movie browsing!
