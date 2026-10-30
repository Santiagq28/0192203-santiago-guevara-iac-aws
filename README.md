<img width="1917" height="965" alt="image" src="https://github.com/user-attachments/assets/60a200d3-5439-4d21-9c8d-d8405013ba56" /># 0192203-Santiago-Guevara-iac-aws

Proyecto del taller de Cloud Computing (Ingeniería de Sistemas – UFPSO).

Despliega automáticamente en AWS una instancia EC2 con Apache y una página web
personalizada. La infraestructura está definida en `templates/template.yaml`
(CloudFormation) y el despliegue lo ejecuta GitHub Actions
(`.github/workflows/deploy.yml`) cada vez que se hace push a la rama `main`.

## Estructura

- `.github/workflows/deploy.yml`: flujo de GitHub Actions
- `templates/template.yaml`: plantilla de CloudFormation (EC2 + Security Group + User Data)
- `README.md`

## Estudiante

- Nombre: Santiago Alberto Guevara Quintero
- Código: 0192203
- Docente: Wilder Andrés Duarte Neira

## Sitio web desplegado

http://34.202.236.126

(La IP cambia si la instancia se vuelve a crear.)
