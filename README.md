
# Personal Website

This repository contains the source code and configuration files for my personal website, built using [MkDocs](https://www.mkdocs.org/). You can view the live demo at [saeedsabet.com](https://saeedsabet.com).

## Getting Started

To use or modify this project, follow the steps below:

### Prerequisites

1. Install Python (ensure it's added to your PATH).
2. Install MkDocs using pip:

```bash
pip install mkdocs
```

### Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/sssabet/personal-website.git
```

2. Navigate to the project's directory:

```bash
cd personal-website
```

3. Install the required dependencies (if any):

```bash
pip install -r requirements.txt
```

### Running the Website Locally

You can preview the website locally by running the following command:

```bash
mkdocs serve
```

Then, open your browser and navigate to `http://127.0.0.1:8000/` to see the website live.

### Building the Static Site

To build the static version of your website, use:

```bash
mkdocs build
```

This will generate a `site/` directory containing all the files for your website.

### Customizing the Website

- To edit the content, modify the markdown files in the `docs/` folder.
- You can customize the theme and other options by editing the `mkdocs.yml` configuration file.

### Deployment

Once your site is built, you can deploy it to GitHub Pages using:

```bash
mkdocs gh-deploy
```

This will automatically push the `site/` folder to a `gh-pages` branch on your repository.

### Demo

You can see the live version of this site at [saeedsabet.com](https://saeedsabet.com).

## Contributing

Feel free to fork this repository and submit pull requests for any improvements or changes you’d like to see!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
