
# Explicación del pipeline:

  Secretos de gihub necesario para su funcionamiento:

`AWS_ACCESS_KEY_ID`

`AWS_SECRET_ACCESS_KEY`

---
### CI


1. Se ejecuta únicamente en la branch master. (Solo si hay cambios dentro del path: src/)

2. Clona el codigo

3. Configura credenciales de AWS

4. Autentica contra ECR

5. Contruye la imagen y la sube a nuestra registry.

  

---

### CD

1. Solo se ejecuta en la branch master.

2. Clona el codigo.

3. Configura credenciales de AWS.

4. Autentica en ECR.

5. Actualiza la imagen de nuestro deployment.