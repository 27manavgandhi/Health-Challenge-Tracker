# Health Challenge Tracker

## Overview

Health Challenge Tracker is a single-page application (SPA) developed using Angular 14+. This application allows users to track their workouts, manage workout data, and visualize workout progress through various features. It is designed to help users maintain their fitness goals and monitor their activities efficiently.

## Features

### User Input
- **Add User Details:** Allows users to input their name, workout type, and workout duration.
- **Workout Tracking:** Records and displays user workout data in a structured format.

### Workout List
- **Search by Name:** Quickly find users by searching their names.
- **Filter by Workout Type:** Filter the workout list based on the type of workout.
- **Pagination:** Efficiently navigate through a large list of users with pagination.

### Data Visualization
- **Workout Progress Charts:** Optionally display users' workout progress using charts for better visualization.

### Storage
- **LocalStorage:** User data is stored locally using `localStorage` for persistence.

### Responsive Design
- **Responsive UI:** The application is designed to be responsive and user-friendly, making it accessible on various devices.

## Screenshots

![](https://github.com/user-attachments/assets/29869083-7ea9-4844-88b0-73f10f2dd8de)
![](https://github.com/user-attachments/assets/dddeac26-2263-4d43-b9c4-041ab0aa12aa)
![](https://github.com/user-attachments/assets/a77a28a5-8679-487d-89fe-2ae4ecd7707f)
![](https://github.com/user-attachments/assets/078f2294-bdf0-404a-ab82-c31338020f1a)


## Getting Started

Follow these steps to run the application locally.

### Prerequisites

- [Node.js](https://nodejs.org/en/)
- [Angular CLI](https://angular.io/cli)

### Installation

1. **Clone the Repository:**
    ```sh
    git clone https://github.com/your-username/Health-Challenge-Tracker.git
    cd Health-Challenge-Tracker
    ```

2. **Install Dependencies:**
    ```sh
    npm install
    ```

### Running the Application

1. **Start the Development Server:**
    ```sh
    ng serve
    ```
    Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

### Code Scaffolding

To generate a new component, use the following command:
```sh
ng generate component component-name
```
You can also use:
```sh
ng generate directive|pipe|service|class|guard|interface|enum|module
```

### Building the Application

To build the project, run:
```sh
ng build
```
The build artifacts will be stored in the `dist/` directory.

### Running Unit Tests

To execute the unit tests via [Karma](https://karma-runner.github.io), run:
```sh
ng test
```
or
```sh
npm run test
```
To execute the unit tests with coverage, run:
```sh
npm run test:cov
```

### Running End-to-End Tests

To execute end-to-end tests via a platform of your choice, run:
```sh
ng e2e
```
Ensure to add a package that implements end-to-end testing capabilities first.

### Further Help

For more help on Angular CLI, use:
```sh
ng help
```
or check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Project Requirements

- **Input Fields:** Add user name, workout type, and minutes with a submit button.
- **Display Data:** Show added users in a table grid.
- **Search & Filter:** Search by username and filter by workout type.
- **Storage:** Use `localStorage` to store data.

```jsx
userData = [
    {
        id: 1,
        name: 'John Doe',
        workouts: [
            { type: 'Running', minutes: 30 },
            { type: 'Cycling', minutes: 45 }
        ]
    },
    {
        id: 2,
        name: 'Jane Smith',
        workouts: [
            { type: 'Swimming', minutes: 60 },
            { type: 'Running', minutes: 20 }
        ]
    },
    {
        id: 3,
        name: 'Mike Johnson',
        workouts: [
            { type: 'Yoga', minutes: 50 },
            { type: 'Cycling', minutes: 40 }
        ]
    }
];
```

- **Initial Data:** Include initial data with 3 users.
- **Pagination:** Add pagination for more than 5 users.
- **Unit Tests:** Include unit tests for one component and one service with 100% coverage.
- **Libraries:** Use libraries like [Angular Material](https://material.angular.io/), [PrimeNG](https://primeng.org/), etc.
- **Deployment:** Host the SPA on a cloud service (e.g., Heroku, Netlify, GitHub Pages).

## Submission

Submit the assignment by filling out [this form](https://forms.gle/ucKCSdcrRh8ApyPX9) with details of the repository and the deployed application. Additionally, record a video introducing yourself, discussing the assignment, and providing feedback.

### Notes

- Ensure the assignment is completed using Angular 14+.
- Feel free to make and mention assumptions in the README.
- Use additional libraries as needed.
- Design can be modified but must include all functionalities.
- Handle all edge cases and bugs.
- Style the application using [Tailwind CSS](https://tailwindcss.com/).

### Deliverables

- Public GitHub repository link with the solution.
- Link to the hosted web application.

### Evaluation Criteria

- Adherence to best practices.
- Well-structured folder hierarchy.
- Code readability and clean coding principles.
- Proper handling of edge cases.
- Visual appeal of the implementation.

### Contact

For any questions, please contact [27manavgandhi@gmail.com](mailto:27manavgandhi@gmail.com).

Happy coding!
