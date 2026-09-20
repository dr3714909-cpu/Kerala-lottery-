# Kerala Lottery Result Checker

A simple green, mobile-friendly static website for checking ticket numbers against locally stored result data.

## Files
- index.html — website
- style.css — design
- results.js — ticket/result database
- script.js — search logic

## Add multiple results
Open `results.js` and add entries inside `RESULTS`.

Example:
"XY123456": {
  winning: true,
  prize: "₹5,000",
  category: "Second Prize",
  draw: "Your Draw Name",
  note: "Verify with the official publication."
}

The key should contain the ticket number without spaces/hyphens.

## Important
This is an interface using data you provide. Verify lottery results with the official Kerala Lottery publication before relying on them.
