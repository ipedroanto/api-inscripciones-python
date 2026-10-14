El entorno virtual crea ejecutando el comando: python -m venv .venv y en Windows powershell se activa con .venv\Scripts\Activate.ps1
Una vez instalado uvicorn, se ejecuta desde la raíz del proyecto con: python -m uvicorn app.main:app --reload
Swagger UI: http://127.0.0.1:8000/docs