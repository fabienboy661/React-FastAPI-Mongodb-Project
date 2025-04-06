🚀 React-FastAPI-MongoDB DevOps Project
📁 Projet : Jenkins, Docker & Kubernetes

Réalisé par : ANDRIANAMBININTSOA Hasiniaina Fabien – L3 IG
📦 Objectif

Mettre en place un projet complet frontend + backend avec un pipeline CI/CD utilisant Jenkins, Docker et Kubernetes.
🛠️ Étapes de mise en place

    Créer un nouveau dossier de projet

    Copier-coller les dossiers suivants dans ce nouveau dossier :

        frontend/

        backend/

        docker-compose.yaml

    Créer un environnement virtuel dans le dossier du backend :

python -m venv env
source env/bin/activate  # (Linux/macOS)
env\Scripts\activate     # (Windows)

Installer Uvicorn (serveur ASGI pour FastAPI) :

    pip install uvicorn

🧩 Dépendances
Frontend – React (à installer avec npm install)

{
  "@emotion/react": "^11.10.5",
  "@emotion/styled": "^11.10.5",
  "@fortawesome/fontawesome-free": "^6.2.0",
  "@mui/icons-material": "^5.10.14",
  "@mui/material": "^5.10.13",
  "@mui/x-data-grid": "^5.17.14",
  "@mui/x-data-grid-generator": "^5.17.14",
  "@testing-library/jest-dom": "^5.16.5",
  "@testing-library/react": "^13.4.0",
  "@testing-library/user-event": "^13.5.0",
  "ant-design-layout": "^4.9.11",
  "antd": "^5.0.3",
  "aos": "^2.3.4",
  "axios": "^1.2.0",
  "bootstrap": "^5.2.2",
  "etd": "^1.0.3",
  "jquery": "^3.6.1",
  "mdb-react-ui-kit": "^5.0.0",
  "mdbreact": "^5.2.0",
  "popper.js": "^1.16.1",
  "react": "^18.2.0",
  "react-bootstrap": "^2.6.0",
  "react-bubbly-transitions": "^1.0.1",
  "react-dom": "^18.2.0",
  "react-icons": "^4.6.0",
  "react-router-dom": "^5.3.4",
  "react-scripts": "5.0.1",
  "react-toastify": "^9.1.1",
  "styled-components": "^5.3.6",
  "web-vitals": "^2.1.4"
}

Backend – FastAPI (à installer avec pip install)

pip install fastapi uvicorn motor pydantic bson anyio fastapi-login pymongo idna mypy-extensions black click colorama h11 passlib pathspec six sniffio starlette tomli asgiref platformdirs python-multipart

🚀 Technologies utilisées

    Frontend : ReactJS, Ant Design, Bootstrap, Axios

    Backend : FastAPI, MongoDB, Pydantic

    CI/CD : Jenkins, GitHub, Docker, Kubernetes
