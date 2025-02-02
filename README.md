# Quick-SIgn-project
This is a signature canvas application made using HTML,CSS and Javascript which Utilizes the HTML canvas element with a 2D context (ctx) for drawing operations, Mouse events handle real-time signature input by dynamically connecting pointer positions.
Uses CSS for Pen color and canvas background that are dynamically updated using color pickers, modifying ctx.strokeStyle and ctx.fillStyle, with backgrounds rendered via ctx.fillRect(). Pen thickness is adjusted through a dropdown.
The Save button captures the canvas as a base64 string via toDataURL() for download and stores it in localStorage.Then the Retrieve button reloads and renders stored content and this app uses Bootstrap for responsive UI and is implemented with modular vanilla JavaScript.
