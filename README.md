# whitepaper
WhitePaper proeycto: GobiernoPublico.com / GobiernoPublico.org
# Gobierno Público

**Tu voz, tu voto — Plataforma democrática descentralizada para una nueva gobernanza ciudadana.**

Gobierno Público es una iniciativa sin fines de lucro que busca empoderar a la ciudadanía para tomar decisiones colectivas mediante votaciones transparentes, verificables y abiertas, utilizando tecnología blockchain y mecanismos DAO.

---

## 🧭 Visión del Proyecto

Crear una democracia más real, directa, accesible y eficaz, donde cada ciudadano pueda proponer, votar y auditar las decisiones colectivas, sirviendo como termómetro y presión política para los gobiernos, sin distinción partidaria.

---

## 🛠️ MVP Actual

Este repositorio contiene el MVP (Producto Mínimo Viable) del sistema dividido en dos plataformas:

- **gobiernopublico.com** — Votación **anónima** con tecnología zk-SNARKs (Testnet Sepolia)
- **gobiernopublico.org** — Votación **identificada** mediante KYC (Red Polygon con Aragon DAO)

### Características:

- Registro mediante wallet (MetaMask u otra compatible)
- Sistema de verificación KYC externo para usuarios de `.org`
- Creación de propuestas ciudadanas o institucionales
- Votación única por propuesta (on-chain)
- Publicación de resultados en tiempo real
- Comparador de sensibilidad social (.com vs .org)
- Panel de transparencia con:
  - Historial personal
  - Hashes de propuestas y votos
  - Código y contratos auditables

---

## 🧱 Tecnologías usadas

- **Frontend**: React, TailwindCSS
- **Blockchain**: Ethereum Sepolia (testnet), Polygon
- **DAO**: Aragon
- **Identidad**: KYC externo (conforme a legislación europea)
- **Privacidad**: zk-SNARKs para anonimato en `.com`
- **Auditoría**: Hashes públicos y código open source

---

## 📁 Estructura del Repositorio

---

## 📄 Contratos inteligentes

- Contrato de propuesta y votación en `.com` (zk-SNARKs, Sepolia)
- Contrato de Aragon DAO en `.org` (Polygon)
- Token de gobernanza único para cada red

---

## 🔐 Privacidad y transparencia

- Los votos son inmutables y públicos (on-chain)
- El código fuente es libre y verificable
- KYC sólo para `.org`, gestionado por entidad externa
- Ninguna wallet puede votar dos veces en la misma consulta

---

## 🫂 Comunidad

Gobierno Público es un proyecto sostenido por voluntarios. Los ciudadanos activos y los roles técnicos son clave para su evolución. La gobernanza del sistema será decidida por los propios usuarios mediante votación.

### Roles comunitarios:

- **Técnicos**: administran el sistema y validan cambios
- **Ciudadanos activos**: mayor poder de voto en `.org`
- **Auditores**: velan por el cumplimiento del código abierto

---

## 🚀 Roadmap (versión simplificada)

| Fase | Hito | Estado |
|------|------|--------|
| Fase 0 | Diseño UI/UX | ✅ Completado |
| Fase 1 | MVP Funcional Web | 🔄 En curso |
| Fase 2 | Integración zk-SNARKs y KYC | ⏳ Planificado |
| Fase 3 | DAO descentralizada y gobernanza propia | 🔜 |
| Fase 4 | App móvil (iOS / Android) | 🔜 |
| Fase 5 | Oráculo de verificación de hechos | 🔜 |

---

## 📢 Licencia

Este proyecto es de código abierto y sin fines de lucro. Está licenciado bajo la [MIT License](LICENSE).

---

**Gobierno Público – Hecho por y para la ciudadanía.**

