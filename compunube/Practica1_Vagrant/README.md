# CONFIGURACIÓN ENTORNO VIRTUALIZADO CON VAGRANT 🏆

### 1. Instalar última versión de VirtualBox 👩‍💻
```
https://www.oracle.com/lad/virtualization/solutions/try-oracle-vm-virtualbox/
```

### 2.Instalar última versión de Vagrant 👩‍💻
```
https://releases.hashicorp.com/vagrant/2.2.19/
```

### 3. Verificar la versión del vagrant e instalar el plugin vbguest 👩‍💻
```
vagrant plugin install vagrant-vbguest
```

## Configuración 🚀

### 1. Crear el vagrant file 👩‍💻
La forma mas facil de crear el archivo vagrantfile es con el comando.
```
vagrant init
```

### 2. Ejecución de las maquinas 👩‍💻
Despues de haber tenido el archivo vagrantfile con las especificaciones necesarias, la ejecución de las maquinas se realiza con el comando.
```
vagrant up
```

### 3. Estado de las maquinas 👩‍💻
Para verificar el estado de las maquinas.
```
vagrant status
```

### 4. Establecer sesión con las maquinas 👩‍💻
Para establecer sesión con las maquinas.
```
vagrant ssh <Nombre de la maquina>
```

### 5. Detener o suspender la maquina 🐾
Para detener la maquina en el estado actual y guardar su estado.
```
vagrant suspend
```

### 5. Apagar la maquina 🐾
Para apagar la maquina.
```
vagrant halt
```
