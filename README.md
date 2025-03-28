# Hwaseong Special City Report Center

This project implements a reporting center web interface for Hwaseong Special City, featuring various types of report submissions and information centers.

## Project Structure

```
project/
├── images/
│   └── header_logo.png
├── tab-corruption.html
├── tab-unfair.html
├── tab-emotion.html
├── tab-internal.html
├── tab-emergency.html
├── index.html
├── styles.scss
├── package.json
└── README.md
```

## Design Links
- [tab-corruption.html](https://www.figma.com/design/TmGs8pzHHfb06T1WMTMJgw/%ED%99%94%EC%84%B1%EC%8B%9C%EB%B3%B5%EC%A7%80%EC%9E%AC%EB%8B%A8-%EB%88%84%EB%A6%AC%EC%A7%91-2025?node-id=1561-4189&t=7B0WfJKsSFVBFNI4-4)
- [tab-unfair.html](https://www.figma.com/design/TmGs8pzHHfb06T1WMTMJgw/%ED%99%94%EC%84%B1%EC%8B%9C%EB%B3%B5%EC%A7%80%EC%9E%AC%EB%8B%A8-%EB%88%84%EB%A6%AC%EC%A7%91-2025?node-id=1561-4322&t=7B0WfJKsSFVBFNI4-4)
- [tab-emotion.html](https://www.figma.com/design/TmGs8pzHHfb06T1WMTMJgw/%ED%99%94%EC%84%B1%EC%8B%9C%EB%B3%B5%EC%A7%80%EC%9E%AC%EB%8B%A8-%EB%88%84%EB%A6%AC%EC%A7%91-2025?node-id=1561-4509&t=7B0WfJKsSFVBFNI4-4)
- [tab-internal.html](https://www.figma.com/design/TmGs8pzHHfb06T1WMTMJgw/%ED%99%94%EC%84%B1%EC%8B%9C%EB%B3%B5%EC%A7%80%EC%9E%AC%EB%8B%A8-%EB%88%84%EB%A6%AC%EC%A7%91-2025?node-id=1561-4595&t=7B0WfJKsSFVBFNI4-4)
- [tab-emergency.html](https://www.figma.com/design/TmGs8pzHHfb06T1WMTMJgw/%ED%99%94%EC%84%B1%EC%8B%9C%EB%B3%B5%EC%A7%80%EC%9E%AC%EB%8B%A8-%EB%88%84%EB%A6%AC%EC%A7%91-2025?node-id=1561-4715&t=7B0WfJKsSFVBFNI4-4)

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