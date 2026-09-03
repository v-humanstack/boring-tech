# ⚙️ ¿cómo construimos nuestro producto? 

Para tener conversaciones reales y no solo repetir palabras clave, acá te comparto cómo está diseñada nuestra arquitectura y por qué tomamos estas decisiones.
 

<img width="670" height="402" alt="Image" src="https://github.com/user-attachments/assets/3f602a7b-6957-47df-bf1b-3295725ae02e" />

## The Beauty Of boring-tech 🛠️

Las reglas tributarias de 5 países cambian rapidísimo. elegimos herramientas robustas para que la complejidad viva en el negocio y no en apagar incendios de infraestructura.

* `Ruby on Rails` • `PostgreSQL` • `TypeScript` • `PHP` • `Kubernetes`

https://github.com/user-attachments/assets/f4f7907d-0197-4e61-a9c6-1dade20e912f

## Cómo se ve por dentro
* **Monolito rails:** el núcleo de nómina que sostiene el producto.
* **Microservicios:** para dominios específicos que requieren independencia.
* **Infra en aws (multi-región):** pensada para absorber los picos masivos de cierre de mes.
* **Frontend:** monorepos con librerías centralizadas para mantener el orden entre productos.


## Cultura de despliegue y aprendizaje 🚀
* **Ci/cd sólido:** alta cobertura de pruebas automatizadas.
* **Feature flags:** desplegamos código sin necesidad de lanzarlo comercialmente de inmediato.
* **Post-mortems sin culpa:** cuando algo falla, el foco está en aprender del sistema, no en buscar culpables.

---
👉 *[mira nuestro código público y cómo conectar en el pilar 3: conversión](LINK_A_PILAR_3)*
