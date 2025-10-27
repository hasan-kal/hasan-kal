# Contribution Snake

This project generates a contribution snake SVG based on the user's GitHub contributions. The SVG is automatically generated using a GitHub Actions workflow that runs daily at midnight UTC and can also be triggered manually.

## How It Works

The GitHub Actions workflow defined in `.github/workflows/snake.yml` checks out the repository, generates the contribution snake SVG, and pushes it to the `output` branch of the repository.

## Contribution Snake

![Contribution Snake](https://raw.githubusercontent.com/hasan-kal/output/main/github-contribution-grid-snake.svg)

## Getting Started

To get started with this project, simply clone the repository and check the `.github/workflows/snake.yml` file for the workflow configuration.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.