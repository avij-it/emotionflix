# Emotion-Based Movie Recommendation System

## Overview

This Python project provides a unique approach to movie recommendations by leveraging web scraping techniques to suggest movies based on emotional categories. By understanding that movies have the power to evoke and explore deep emotions, this system helps users find films that resonate with their current emotional state.

## Key Concepts

### Web Scraping
Web scraping is an automated technique for extracting data from websites. This project uses web scraping to retrieve movie titles from IMDb, demonstrating how to:
- Access web pages programmatically
- Parse HTML content
- Extract structured movie information

### Emotional Movie Selection
Movies are more than entertainment; they are emotional journeys that:
- Evoke empathy
- Provide self-reflection
- Connect viewers with character experiences

## Features

- Recommend movies based on emotional categories
- Scrape movie titles from IMDb
- Support multiple emotional genres
- Simple command-line interface
- Error handling for web requests

## Technologies Used

- **Python 3.7+**
- **Libraries**:
  - `requests`: For making HTTP requests
  - `BeautifulSoup`: HTML parsing
  - `lxml`: HTML/XML processing
- **Web Scraping Techniques**:
  - User-Agent rotation
  - Error handling
  - Regular expression matching

## Prerequisites

- Python 3.7 or higher
- pip package manager

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/emotion-movie-recommender.git
cd emotion-movie-recommender
```

2. Install required dependencies:
```bash
pip install requests beautifulsoup4 lxml
```

## Usage

Run the script and select an emotion:

```bash
python movie_recommender.py
```

### Supported Emotions/Genres

- Drama
- Action
- Comedy
- Horror
- Crime

## Example

```
Enter the emotion: Drama
(Outputs a list of drama movie titles)
```

## Web Scraping Approach

1. Define IMDb genre URLs
2. Send HTTP requests with custom headers
3. Parse HTML using BeautifulSoup
4. Extract movie titles using regex
5. Handle potential network and parsing errors

## Limitations

- Depends on IMDb's current website structure
- Limited to predefined emotional categories
- Requires active internet connection
- No detailed movie information beyond titles

## Error Handling

- Validates user input
- Catches network request exceptions
- Provides user-friendly error messages

## Future Improvements

- Expand emotional categories
- Add movie details (ratings, year)
- Implement caching mechanisms
- Create more sophisticated recommendation algorithms

## Ethical Considerations

- Respect IMDb's terms of service
- Implement responsible web scraping practices
- Add delay between requests to avoid overloading servers

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## License

Distributed under the MIT License. 

## Disclaimer

This project is for educational purposes. Always respect website terms of service when web scraping.

## Resources

- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/)
- [Requests Library](https://docs.python-requests.org/)
- [Web Scraping Best Practices](https://www.scraperapi.com/blog/web-scraping-best-practices)

## Contact

For questions or suggestions, please open an issue in the GitHub repository.
