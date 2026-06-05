const express = require("express");
const cors = require("cors");

const app = express();
app.use(cors());
app.use(express.json());

app.post("/obecnosc", (req, res) => {
  const { name, status } = req.body;

  console.log("Obecność:", name, status);

  res.json({ ok: true });
});

app.listen(3000, () => {
  console.log("Serwer działa na porcie 3000");
});
