# Property Search Portal

A centralized system for searching property information in Delhi, including ownership details and encumbrance information.

## Features

- **Property Search**: Search for properties by ID or address
- **Ownership Details**: View detailed information about property owners
- **Encumbrance Check**: Verify if properties have any loans, mortgages, or encumbrances
- **Property Status**: Color-coded status indicators (red for mortgaged properties, green for clear titles)
- **PDF Download**: Generate property summary reports in PDF format
- **Responsive Design**: Works seamlessly on both mobile and desktop devices

## Technology Stack

- **Frontend**: React with JavaScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Data**: Mock data for property information (simulating government databases)

## Project Structure

```
Arcane_V2/
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── data/           # Mock data
│   │   ├── pages/          # Page components
│   │   ├── routes/         # Routing configuration
│   │   └── ...
│   └── ...
└── server/                 # Backend server (Express)
    └── ...
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies for both client and server:

```bash
# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
```

3. Start the development servers:

```bash
# Start the client
cd client
npm run dev

# Start the server
cd ../server
npm start
```

4. Open your browser and navigate to `http://localhost:5173`

## Usage

1. Navigate to the home page
2. Click on "Start Property Search" or "Search Properties"
3. Use the search bar to find properties by ID or address
4. Apply filters for property type and status
5. Click on a property card to view detailed information
6. Download property information as PDF if needed

## Mock Data

The application uses mock data to simulate property information that would typically be retrieved from government databases such as DORIS, DLR, and CERSAI. In a production environment, this would be replaced with real API calls to these services.


