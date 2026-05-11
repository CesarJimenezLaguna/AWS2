# AWS

## 1. Web estática formato currículum con S3 y CloudFront

### 1.1 Creación del backet en S3

![Bucket S3](./images/s3-cloudfront/bucket-s3.png)

#### 1.1.1 Contenido del bucket (index.html)

![Resume Web](./images/s3-cloudfront/contenido-s3.png)

### 1.2 Creación de la distribución en CloudFront

![CloudFront](./images/s3-cloudfront/cloudfront-distribucion.png)

### 1.3 Contenido de la Web

![Web](./images/s3-cloudfront/web-resume.png)

## 2. Configuración de Amazon Cognito

### 2.1 Creación de la pool de usuarios

![Users Pool](./images/cognito/cognito-pool-usuarios.png)

### 2.2 Registrar usuario en Cognito

**Configuración**

![Usuario en Cognito](./images/cognito/cognito-usuario-creado.png)

**Feedback**

![Creación exitosa](./images/cognito/cognito-feedback-creacion-usuario.png)

### 2.3 Redirección a la web creada tras realizar el log-in

**Configuración URL de redirección por defecto**

![](./images/cognito/cognito-configuracion-url-redireccion.png)

**Funcionamiento de la redirección**

<video src="./images/cognito/cognito-redireccion-web.mov" controls width="100%"></video>




![](.)
