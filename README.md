# ⚙️ ¿cómo construimos nuestro producto? 

para tener conversaciones reales y no solo repetir palabras clave, acá te comparto cómo está diseñada nuestra arquitectura y por qué tomamos estas decisiones.
 

https://github.com/user-attachments/assets/a0410797-6126-4850-b6e8-396c3cf6addf

## ¿buk es boring-tech? 🛠️

las reglas tributarias de 5 países cambian rapidísimo. elegimos herramientas robustas para que la complejidad viva en el negocio y no en apagar incendios de infraestructura.

* `Ruby on Rails` • `PostgreSQL` • `TypeScript` • `PHP` • `Kubernetes`

## cómo se ve por dentro
* **monolito rails:** el núcleo de nómina que sostiene el producto.
* **microservicios:** para dominios específicos que requieren independencia.
* **infra en aws (multi-región):** pensada para absorber los picos masivos de cierre de mes.
* **frontend:** monorepos con librerías centralizadas para mantener el orden entre productos.


## cultura de despliegue y aprendizaje 🚀
* **ci/cd sólido:** alta cobertura de pruebas automatizadas.
* **feature flags:** desplegamos código sin necesidad de lanzarlo comercialmente de inmediato.
* **post-mortems sin culpa:** cuando algo falla, el foco está en aprender del sistema, no en buscar culpables.

---
👉 *[mira nuestro código público y cómo conectar en el pilar 3: conversión](LINK_A_PILAR_3)*
