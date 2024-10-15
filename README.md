# Kanban Board Application

This project is an interactive Kanban Board built using **ReactJS** that interacts with an API. The app allows users to group and sort tickets in various ways, providing a responsive and visually appealing user experience.

## Features

### Grouping Options:
- **By Status**: Group tickets based on their current status.
- **By User**: Arrange tickets according to the assigned user.
- **By Priority**: Group tickets based on their priority level.

### Sorting Options:
- **Priority**: Arrange tickets in descending order of priority.
- **Title**: Sort tickets in ascending order based on the ticket title.

### Additional Features:
- **Responsive Design**: The Kanban board is responsive, ensuring a smooth user experience across devices.
- **Data Persistence**: The app saves the user’s view state, even after a page reload.

## Installation and Setup Instructions

### Prerequisites
- **Node.js** (v14 or later) and **npm** installed on your machine.

### Steps to run the project:

1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the project directory**:
    ```bash
    cd kanban-board
    ```

3. **Install dependencies**:
    ```bash
    npm install
    ```

4. **Start the application**:
    ```bash
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000/` to see the Kanban board in action.

## API Endpoint:
The application interacts with the following API to fetch data:
- [Quicksell API](https://api.quicksell.co/v1/internal/frontend-assignment)

## Project Components

- **KanbanBoard.js**: Main component rendering the Kanban board.
- **TicketCard.js**: Component for rendering individual ticket cards.
- **Header.js**: Component for user interaction (grouping/sorting).
- **api.js**: Utility file for handling API interactions.
- **App.js**: The root component.
- **App.css**: Contains styling for the app.

## Usage

Once the application is running:

- **Display Tickets**:
  - Click the "Display" button to fetch and display tickets from the API.

- **Group Tickets**:
  - Select any of the grouping options from the dropdown to group the tickets by **Status**, **User**, or **Priority**.

- **Sort Tickets**:
  - Select a sorting option to arrange the tickets by **Priority** (descending order) or **Title** (ascending order).

## Assets
The assets used to build the UI can be found [here](#).

## Evaluation Criteria

- **Functionality**: The app fetches data from the provided API and allows users to group and sort tickets.
- **Visual Design**: The UI matches the provided design and layout.
- **Business Logic Optimization**: Efficient grouping and sorting mechanisms are used.
- **Component Structuring**: The project promotes reusability and maintainability through well-structured components.

## Technologies Used

- **ReactJS**: For building the user interface.
- **Pure CSS**: No external CSS frameworks or libraries like Bootstrap, Tailwind, etc., have been used.
- **Styled JSX**: For scoped CSS styling.
- **JavaScript**: For implementing business logic.

## Future Improvements

- Add **drag-and-drop functionality** to enhance the Kanban board experience.
- Include a filter for tickets based on additional attributes like tags or due dates.
- Improve accessibility with better keyboard navigation and ARIA labels.

## License

This project is licensed under the [MIT License](./LICENSE).
