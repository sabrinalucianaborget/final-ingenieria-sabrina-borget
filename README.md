# Final Ingeniería – Sabrina Borget

Este proyecto contiene una app mínima con estilo pastel para la entrega final.

## Datos
- **Nombre:** Sabrina Borget
- **Legajo:** 84330

## Docker
### Construir imagen
```
docker build -t final-ingenieria .
```

### Ejecutar contenedor
```
docker run -d -p 8080:80 final-ingenieria
```

## Git
### Subir proyecto a GitHub
```
git init
git add .
git commit -m "Proyecto inicial"
git remote add origin <URL-del-repo>
git branch -M main
git push -u origin main
```
