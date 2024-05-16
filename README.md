# Redes
# ● Actividad 6.1 - Creación de una red LAN utilizando máquinas virtuales:
Configura VirtualBox para establecer una red de área local (LAN) en la que se
conecten dos máquinas virtuales:
Investiga sobre los siguientes tipos de red que permite establecer VirtualBox:
# ● NAT.
La máquina virtual se conecta a la red a través de la dirección IP del host. Las conexiones desde la máquina virtual hacia el exterior. Las conexiones desde la máquina virtual hacia el exterior funcionan, pero no se puede acceder desde la red externa directamente. 
[Máquina virtual]->[Host]->[Internet]
# ● Adaptador puente.
La máquina virtual actúa como un dispositivo más en la misma red del host. Tiene una propia IP en la red local.
[Máquina virtual]->[Router]->[Internet]
# ● Red interna.
Las máquinas virtuales pueden estar comunicadas entre ellas. No tienen acceso al host ni a internet.
[Maquina virtual 1]->[Red interna]->[Maquina virtual 2]
# ● Red NAT
Permite comunicarse a varias máquinas virtuales en la misma red NAT y también con Internet, pero con la capacidad adicional de permitir que las máquinas virtuales se vean entre sí.
[Máquina virtual 1]->[Red Nat]->[Máquina virtual 2] 
