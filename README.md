# Clock App

The Date constructor function builds objects storing the current date and time.

The toLocaleTimeString method returns a localized string representation of the time portion of the date.

The useState hook allows us to add the current date as state into a function component.

The setInterval utility creates a timer running the given callback function at the specified intervals.

The useEffect hook lets us running effects in function components. By sending an empty array as the second 
argument to useEffect we can start the timer only once not at every rerender.