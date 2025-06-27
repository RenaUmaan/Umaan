from fastapi import FastAPI

app = FastAPI()

@app.get("/saludo")
def saludo(nombre: str = "amigo"):
    return {"saludo": f"Hola, {nombre} 👋"}
