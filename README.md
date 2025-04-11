body {
    font-family: 'Arial', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #f4f4f9;
}

.calculator {
    border: 1px solid #ccc;
    border-radius: 5px;
    width: 300px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.calculator-screen {
    width: 100%;
    height: 80px;
    background-color: #252525;
    color: #fff;
    border: none;
    text-align: right;
    padding-right: 20px;
    padding-left: 10px;
    font-size: 2.5rem;
}

.calculator-keys {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
    padding: 20px;
}

button {
    height: 60px;
    font-size: 1.5rem;
    border: none;
    border-radius: 5px;
    background-color: #eaeaea;
    box-shadow: 0 2px 2px rgba(0,0,0,0.1);
    cursor: pointer;
}

button:active {
    background-color: #d4d4d4;
}

.operator {
    background-color: #ff9500;
    color: #fff;
}

.operator:active {
    background-color: #e08900;
}

.equal-sign {
    background-color: #ff9500;
    color: #fff;
    grid-column: span 2;
}

.equal-sign:active {
    background-color: #e08900;
}

.all-clear {
    background-color: #ff3b30;
    color: #fff;
}

.all-clear:active {
    background-color: #d32f2f;
}

.decimal {
    background-color: #eaeaea;
}