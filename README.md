Step 1: Add showChart and setShowChart
to SkewedNavbar.js

- In your SkewedNavbar.js component, make
sure you are receiving showChart and 
setShowChart as props.

Step 2: Modify handleCompletedClick
in SkewedNavbar.js

- Inside SkewedNavbar.js, modify your
handleCompletedClick function to toggle
the showChart state using the
setShowChart function received as a prop.

Step 3: Pass showChart and setShowChart
as props

- In your App.js component, make sure you
are passing showChart and setShowChart
as props to the SkewedNavbar component.
- Declare a chartRef using the useRef hook.
- Create a function named closeCompletedHabits
that sets both showCompletedHabits and
showChart to false.
- Pass the closeCompletedHabits function as
a prop named onClose to the CompletedHabits component

Step 4: Modify App.js to conditionally
render the chart

- Wrap your chart rendering code in App.js inside
a conditional check for showChart. Only render
the chart when showChart is true.

Step 5: Modify the useEffect hook to
conditionally render the chart

- In your App.js, modify the useEffect 
to handle chart rendering conditionally.


