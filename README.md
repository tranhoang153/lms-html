# Hwaseong Special City Report Center

This project implements a reporting center web interface for Hwaseong Special City, featuring various types of report submissions and information centers.

## Project Structure

```
project/
├── images/
│   └── header_logo.png
├── tab-corruption.html (tab 부패신고)
├── tab-unfair.html (tab 부조리신고 안내)
├── tab-emotion.html (tab 갑질신고·지원센터 안내)
├── tab-internal.html (tab 내부부패공익신고 안내)
├── tab-emergency.html (tab 청탁금지법위반신고)
├── index.html
├── styles.scss
├── package.json
└── README.md
```

## Setup

1. Clone the repository:

```bash
git clone [repository-url]
cd [project-directory]
```

2. Install dependencies:

```bash
npm install
```

## Running the Project

1. Start the SCSS compiler in watch mode:

```bash
npm run sass
```

2. Run index.html file

## Features

- Dynamic tab switching without page reload
- Form submission for corruption reports
- Information centers for various types of reports
- Responsive design
- Modern UI with SCSS styling

## Development

- The SCSS will automatically compile when changes are made
- Each tab's content is in a separate HTML file for easier maintenance
- Images should be placed in the `images` directory

## File Structure Explanation

- `index.html`: Main entry point and structure
- `styles.scss`: Main stylesheet (compiles to styles.css)
- `tab-*.html`: Individual content files for each tab
- `images/`: Directory containing all image assets

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Create a new branch for your feature
2. Make your changes
3. Submit a pull request

## Notes

- The SCSS compiler will create a `styles.css` file which is ignored by git
- Make sure to run both the SCSS compiler and the local server for development
