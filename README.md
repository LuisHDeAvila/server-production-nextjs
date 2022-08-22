# Aplicaciones Web (next js, typescript, y docker)
Entorno de produccion de aplicaciones web *serverless* (sin servidor).
Orientado principalmente a escalabilidad de interfaces de aplicaciones web.

## Uso
```
  yarn
  yarn dev
```

## testing
```
	docker run --name=next-app -p 3000:3000 nextjs-initial
```

## Generar la imagen de docker
Primero
```
	yarn
	yarn build
	yarn start
```
o
```
	npm install
	npm build
	npm start
```

Generar imagen docker:
```
	docker build -t next-prod-ts .
```

### Anexos:
Para mas informacion consulta la documentacion oficial.