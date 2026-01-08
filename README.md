# Dark Series - Interactive Family Network Graph 🕸️

An interactive network graph visualization that maps out the incredibly complex family tree and character relationships from the Netflix series "Dark". Navigate through the tangled web of time-traveling families across multiple generations.

## 🌐 Live Demo

**[View the Interactive Visualization](https://dark-network-graph.netlify.app/)**

## 📖 About

"Dark" is known for having one of the most intricate family trees in television history, with characters traveling through time and creating paradoxical relationships. This project visualizes these connections in an interactive network graph, making it easier to understand how the families are interconnected across different time periods.

## ✨ Features

- **Interactive Network Graph**: Explore the family connections with a dynamic, physics-based network visualization
- **Color-Coded Families**: Each family has a distinct color for easy identification:
  - Tiedemen family
  - Tauber family
  - Nielsen family
  - Kahnwald family
  - Doppler family
- **Character Information**: Click on any character node to view detailed information from the Dark Wiki
- **Responsive Design**: Works seamlessly across different screen sizes
- **Dark Theme**: UI design matches the atmospheric tone of the series

## 🛠️ Technologies Used

- **React** - Frontend framework
- **Highcharts** - Network graph visualization with physics simulation
- **Material-UI** - Component library for modern UI elements
- **Create React App** - Project scaffolding and build tools

## 🚀 Getting Started

### Prerequisites

- Node.js (v12 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/saitama-solutions/dark-series-character-network.git
cd dark-network-graph
```

2. Install dependencies:
```bash
yarn install
# or
npm install
```

3. Start the development server:
```bash
yarn start
# or
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## 📦 Available Scripts

### `yarn start`
Runs the app in development mode at [http://localhost:3000](http://localhost:3000). The page will reload when you make edits.

### `yarn build`
Builds the app for production to the `build` folder. The build is optimized for best performance.

### `yarn test`
Launches the test runner in interactive watch mode.

## 🎨 How It Works

The application uses Highcharts' network graph module to create an interactive visualization where:

1. Each node represents a character from the series
2. Edges (connections) represent parent-child relationships
3. The physics simulation arranges nodes to minimize overlapping
4. Clicking on a node opens a modal with the character's wiki page
5. Node colors are determined by the character's family name

The family tree data is maintained in `src/data.js`, making it easy to update or extend the graph.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs or issues
- Suggest new features
- Submit pull requests to improve the visualization

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Credits

- Character data sourced from [Dark Netflix Fandom Wiki](https://dark-netflix.fandom.com/)
- Inspired by the brilliant Netflix series "Dark"

## ⚠️ Spoiler Warning

This visualization contains information about character relationships throughout all three seasons of Dark. If you haven't finished the series, proceed at your own risk!

---

**Note**: This is a fan-made project and is not officially affiliated with Netflix or the creators of "Dark".
