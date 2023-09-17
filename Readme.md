# Reto Integración y Control de Sistemas Robóticos
## Instalación
Clona el workspace localmente, instala los requerimientos y compila
```bash
git clone https://github.com/RoBorregos/reto_integracion_serial
cd reto_integracion_serial
catkin_make
```
Instala los requerimientos
```bash
cd reto_integracion_serial/src
pip install -r requirements.txt
```

## Ejecución
Con un roscore activo, ejecuta el nodo de ROS
```bash
cd reto_integracion_serial
source devel/setup.bash
rosrun motor motor_node.py
```
## Uso
Revisa los tópicos disponibles
```bash
rostopic list
```
Sigue las instrucciones del [reto](https://drive.google.com/file/d/1In8nf-ihflCYbr-yOIKbBM4cxvXmJ7gi/view?usp=sharing)