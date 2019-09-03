# Evaluación de automatización
## Puntos a evaluar
1. Crear una máquina virtual con Vagrant y provisiona un docker engine con Ansible o Puppet. Recomendamos usar ansible-playbook local o puppet apply, evita las ejecuciones remotas con inventario de ansible o puppet-master.
2. Despliega una aplicación dockerizada sobre la VM usando Ansible y docker-compose.
3. Crear un repositorio en Github con todos los archivos necesarios para crear la infraestructura virtual y un README file con la documentación para replicar el escenario y un diagrama que explique el flujo.
4. Si puedes hacer todo esto sobre un orquestador como docker swarm o kubernetes suma puntos.
## Requisitos
Para poder ejecutar este código se necesita contar en el host con:
* vagrant 2.2.3
* ansible 2.8.4

## Ejecución de prueba
```
git clone https://github.com/fahumadar/laboratorio_devops.git
cd laboratorio_devops
vagrant up
```
