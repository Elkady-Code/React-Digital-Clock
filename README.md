# Digital Clock

A simple digital clock built with React.js using the `useState` and `useEffect` hooks. This application displays the current time and updates it every second.

## Display

![digital-clock](image.png)

## Features

- Displays current time in a 12-hour format with AM/PM
- Updates every second to reflect the current time
- Uses React hooks for state management and side effects

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Elkady-Code/digital-clock.git

2. Navigate to the project directory:
    ```bash
    cd react-digital-clock

3. Install the dependencies:
    ```bash
    npm install

4. Start the development server:
    ```bash
    npm run dev
    
## Usage

- The DigitalClock component can be used in any React application. Simply import it and include it in your JSX:
    ```javascript
    import DigitalClock from './DigitalClock';
        function App() {
           return (
             <div>
                 <h1>My Digital Clock</h1>
                    <DigitalClock />
            </div>
             );
         }

## Technologies Used
- React.js
- JavaScript (ES6)
- CSS (for styling)

## License

- This project is licensed under the MIT License 


