## How to run

Clone the repository and open the project folder in VS Code. Since I built the app using vanilla HTML, CSS, and JavaScript, no extra installation is required. Simply open the `index.html` file in the browser or use the VS Code Live Server extension for a better development experience. If deployed, the live URL can also be accessed directly in the browser.
or Live Demo Link: https://nimrahnaeem192.github.io/Pomodoro_Timer_Assessment/

## Stack & design choices

I used vanilla HTML, CSS, and JavaScript because it is lightweight, fast to build, and enough for a single-page timer application without adding framework complexity. One design decision I made was keeping the timer text very large and centered so users can quickly read it even from a distance while focusing. Another decision was placing all controls in a single horizontal section because it reduces unnecessary movement and improves usability during active sessions.

## Responsive & accessibility

On a 360px mobile screen, the layout stacks vertically and keeps buttons full-width for easier tapping, while on a 1440px laptop the content stays centered with more spacing for readability. For accessibility, I added proper button labels and visible focus states for keyboard navigation. One thing I did not fully implement was advanced screen reader announcements for timer state changes because of time limitations.

## AI usage

I used ChatGPT to understand timer logic, state handling, and frontend structure planning. I also used it to brainstorm UI layout ideas and localStorage handling for saving session history. One thing I changed from the AI suggestion was the button layout, the original suggestion used equal fixed widths, but I changed it to a flexible layout so the controls adapt better on smaller screens.

## Honest gap

One area that is not fully polished is the session history UI because it is functional but visually simple. With another day, I would improve animations, add smoother transitions between focus and break modes, and create a more detailed statistics section for daily productivity tracking.
