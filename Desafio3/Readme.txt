Objetivos del desafío:

Gestión de Cuentas y Usuarios
	Creación y Configuración de Cuentas:
		Proceso de crear una cuenta en AWS, fundamental para cualquier trabajo en la nube.
	
	Gestión de Identidades y Accesos (IAM):
		Creación de usuarios con permisos específicos.
		Otorgar permisos de administrador mediante políticas de acceso (admin full access).
		Importancia de iniciar sesión con diferentes usuarios para tareas específicas.
Organización y Etiquetado de Recursos
	Uso de Tags:
		Cómo definir y aplicar tags para organizar y gestionar recursos.
		Importancia de etiquetar recursos con información relevante como propietario, equipo y proyecto.

Implementación y Configuración de Servicios Específicos
	Amazon EC2:
		Lanzamiento de instancias EC2 dentro de los límites del free tier.
		Automatización de configuraciones iniciales usando scripts en User Data.
		Configuración de Security Groups para gestionar el tráfico de red.

Conexión Remota a Instancias:
	Configuración y verificación de conexiones remotas utilizando SSM, llaves SSH o desde una VM con Linux.

Amazon S3:
	Creación de buckets con nombres únicos.
	Subida y gestión de archivos en un bucket S3.
	Verificación de la funcionalidad del bucket y de los archivos subidos.

Amazon EBS:
	Creación y vinculación de volúmenes EBS a instancias EC2.
	Configuración del sistema de archivos (ext4), incluyendo formateo y montaje.
	Actualización del FSTAB para montaje automático y verificación de la capacidad de escritura en el volumen.

Operaciones Básicas y Buenas Prácticas
	Automatización y Scripting:
		Uso de scripts para instalar software y realizar configuraciones iniciales.
		Descarga de archivos desde S3 usando herramientas como AWS CLI o wget.
	Configuración de Seguridad:
		Configuración de reglas de seguridad para gestionar acceso a los recursos.
		Importancia de asegurar conexiones remotas y permisos adecuados.
	Gestión de Almacenamiento:
		Montaje y verificación de sistemas de archivos.
		Movilidad de datos entre diferentes servicios (por ejemplo, desde S3 a un volumen EBS).

