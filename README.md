# React Clock (Hello Logical!)

This is a simple project that demonstrates the use of React via CDN in a basic HTML file to display the current time, updating every second.

## Features

- Live digital clock using React state and effect hooks
- Simple, single-file implementation (no build tools or frameworks needed)
- Clean and minimal setup

## How It Works

- Uses `React.createElement` to render content.
- Utilizes `useState` and `useEffect` to track and update the current time every second.
- Runs entirely in the browser using the React and ReactDOM UMD builds.

## Usage

1. Clone or download the repository.
2. Open `index.html` in any modern browser.
3. You’ll see a header displaying:  
   `Hello Logical!, it's [current time]`, which updates every second.

## Dependencies

- [React 18 (Development UMD)](https://unpkg.com/react@18/umd/react.development.js)
- [ReactDOM 18 (Development UMD)](https://unpkg.com/react-dom@18/umd/react-dom.development.js)
