# Ethical Movie Recommendations

## Overview

The Ethical Movie Recommendations project is an innovative approach to movie recommendation systems, prioritizing user sensitivity and content preferences. By allowing users to specify both desired and undesired content, we aim to create a safer, more personalized movie-watching experience.

## Objective

Our primary goal is to demonstrate the importance of ethical considerations in recommendation systems. We achieve this by developing a sensitive movie recommendation system that respects users' preferences for what they want to see and what they wish to avoid, especially regarding potentially triggering or inappropriate material.

## Features

- User-friendly interface built with Altair
- Dual input system for desired and undesired content
- Integration of movie ratings from user reviews
- Movie poster display (where available)
- Detailed movie information tooltips

## Data Sources

1. **MovieLens**: 25 million ratings and one million tag applications for 62,000 movies by 162,000 users. [Dataset](https://files.grouplens.org/datasets/movielens/ml-25m.zip)
2. **IMDB Reviews**: 5,571,499 unique reviews. [Dataset](https://www.kaggle.com/datasets/ebiswas/imdb-review-dataset)
3. **Movie Posters**: 41,979 unique poster URLs. [Dataset](https://www.kaggle.com/datasets/dadajonjurakuziev/movieposter)

## Methodology

### Data Manipulation
- Text data cleaning and processing
- Porter Stemming algorithm for tag normalization
- Dataset joining for comprehensive movie information
- Dask utilization for large dataset handling

### Analysis
- Exploration of rating distributions
- Identification of popular genres
- User sentiment analysis through word clouds

## Installation

```bash
git clone https://github.com/your-username/ethical-movie-recommendations.git
cd ethical-movie-recommendations
pip install -r requirements.txt
```

## Usage

```bash
python main.py
```

Navigate to the provided local URL to access the user interface.

## Contributing

We welcome contributions! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to submit pull requests, report issues, or request features.

## Acknowledgements

We'd like to thank the creators and maintainers of the MovieLens, IMDB, and Movie Poster datasets for making their data available for research and development.

## References

- Halevy, A. (2022, December 28). Your Personal Data Timeline: Data timelines will protect your privacy and make AI better. DeepLearning.AI The Batch.
- Alfaddagh, M. (2020, January 3). What Are the Top Rated 25 Movies? Medium.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
