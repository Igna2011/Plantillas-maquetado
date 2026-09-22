* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}





body {
    font-family: sans-serif;
    background-color: #f4f6f9;
}







.top {
    background-color: #1e293b;
    width: 100%;
    height: 200px;
    display: flex;
    align-items: center;
    padding: 0 50px;
    gap: 40px;
}







.cuadrado {
    background-color: #3b82f6;
    width: 140px;
    height: 140px;
    flex-shrink: 0;
}







.lineas-top {
    display: flex;
    flex-direction: column;
    gap: 12px;
    width: 100%;
    max-width: 500px;
}







.linea {
    background-color: #475569;
    height: 10px;
    width: 85%;
}







.linea.larga-top {
    background-color: #64748b;
    height: 14px;
    width: 40%;
    margin-bottom: 5px;
}







.centre {
    background-color: #ffffff;
    width: 100%;
    min-height: 450px;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 40px 0;
}







.grilla {
    display: grid;
    grid-template-columns: repeat(3, 140px);
    grid-template-rows: repeat(2, 140px);
    gap: 40px 60px;
}







.caja-item {
    border: 16px solid transparent;
}





.item-azul {
    background-color: #a5f3fc;
}




.item-rosa {
    background-color: #fbcfe8;
}




.item-violeta {
    background-color: #ddd6fe;
}





.abajo {
    background-color: #0f172a;
    width: 100%;
    height: 120px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 0 10%;
}







.columna-footer {
    display: flex;
    flex-direction: column;
    gap: 8px;
    width: 120px;
}







.linea-footer {
    background-color: #334155;
    height: 6px;
    width: 100%;
}








.linea-footer.corta {
    background-color: #516177;
    height: 8px;
    width: 60%;
}
