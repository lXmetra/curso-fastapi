# Dos formas de ejecutar fastapi
    1. uvicorn main:app en la terminal
    2. Agregar las líneas de código:
        import uvicorn
        if __name__=="__main__":
            uvicorn.run("main:app", port=8000)

        Y luego correr main.py