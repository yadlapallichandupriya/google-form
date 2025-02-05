const express = require("express");
const { google } = require("googleapis"); // Ensure googleapis is installed

const app = express();

app.get("/", (req, res) => {
    res.send("Hello World!");
});

// ✅ Corrected app.listen() (Removed incorrect req, res parameters)
app.listen(1337, () => console.log("Server running on port 1337"));
