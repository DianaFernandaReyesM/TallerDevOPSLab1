
# Taller DevOps - Laboratorio 1

Proyecto de laboratorio DevOps que implementa una API REST
utilizando FastAPI.

## Funcionalidades

- GET /: Saludo personalizado mediante first_name y last_name.
- GET /health: Verificación del estado de salud de la API.

## Tecnologías

- Python 3.12
- FastAPI
- Poetry
- Docker
- GitHub Actions
- AWS

## Pipeline CI/CD

El proyecto utiliza GitHub Actions para:

1. Verificar la calidad del código con Pylint.
2. Ejecutar pruebas unitarias con Pytest.
3. Construir y publicar una imagen Docker en Amazon ECR.
4. Desplegar la aplicación en Amazon ECS.
