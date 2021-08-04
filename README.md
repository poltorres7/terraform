Terraform notes
===============

### Comandos

Ejecuta los siguientes comandos:

> [!IMPORTANT]
> Recuerda tener configuradas tus SK y AK de AWS para poder ejecutar estos comandos

```bash
#valida que el template sea correcto
terraform validate

#aplica el template
terraform apply
# pedirá confirmación 

# mostrará los recursos creados
terraform show

# destruye la infraestructura creada
terraform destroy
```