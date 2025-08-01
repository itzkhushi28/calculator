body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #222;
  font-family: Arial, sans-serif;
}

.calculator {
  border: 2px solid #444;
  padding: 20px;
  border-radius: 12px;
  background-color: #111;
  box-shadow: 0 0 10px #000;
}

#display {
  width: 100%;
  height: 50px;
  font-size: 24px;
  margin-bottom: 15px;
  text-align: right;
  padding-right: 10px;
  border: none;
  background: #000;
  color: #0f0;
  border-radius: 5px;
}

.buttons {
  display: grid;
  grid-template-columns: repeat(4, 60px);
  gap: 10px;
}

button {
  height: 60px;
  font-size: 20px;
  border: none;
  border-radius: 8px;
  background-color: #333;
  color: white;
  cursor: pointer;
  transition: background-color 0.2s ease;
}

button:hover {
  background-color: #555;
}

button.zero {
  grid-column: span 2;
}
