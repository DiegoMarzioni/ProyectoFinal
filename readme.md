









<div align="center">
	<img src="./logo.jpg" alt="DevCore Proyecto" width="600"/>
	<h1>🎓 Proyecto Final - Plataforma de Cursos</h1>
	<p>Plataforma web moderna para gestión y venta de cursos, desarrollada con <b>Next.js</b> y <b>NestJS + TypeORM</b>.</p>
	<br/>
	<hr/>
	<h3>🔎 Vista previa del proyecto</h3>
	<table>
		<tr>
			<td align="center"><img src="https://res.cloudinary.com/dvwpxy4kh/image/upload/v1764053854/1_iw6i82.png" alt="Vista previa 1" width="320"/></td>
			<td align="center"><img src="https://res.cloudinary.com/dvwpxy4kh/image/upload/v1764053854/3_wkioh7.png" alt="Vista previa 2" width="320"/></td>
		</tr>
		<tr>
			<td align="center"><img src="https://res.cloudinary.com/dvwpxy4kh/image/upload/v1764053854/2_bmzltz.png" alt="Vista previa 3" width="320"/></td>
			<td align="center"><img src="https://res.cloudinary.com/dvwpxy4kh/image/upload/v1764053854/4_tk1ily.png" alt="Vista previa 4" width="320"/></td>
		</tr>
		<tr>
			<td align="center"><img src="https://res.cloudinary.com/dvwpxy4kh/image/upload/v1764053854/5_guarom.png" alt="Vista previa 5" width="320"/></td>
			<td align="center"><img src="https://res.cloudinary.com/dvwpxy4kh/image/upload/v1764053853/6_lh93ei.png" alt="Vista previa 6" width="320"/></td>
		</tr>
	</table>
</div>


---

## 🚀 Descripción

Este proyecto es una plataforma de cursos online que permite a los usuarios explorar el catálogo, gestionar su carrito, comprar cursos y administrar su perfil. Incluye autenticación, panel de usuario, panel de administración y una experiencia visual atractiva.

---

## 🛠️ Tecnologías

**Frontend:**
- Next.js 16
- React 19
- TailwindCSS
- Formik, Yup

**Backend:**
- NestJS
- TypeORM
- PostgreSQL
- JWT, Bcrypt
- Nodemailer

---

## 📁 Estructura de Carpetas

```bash
ProyectoFinal/
├── back/        # Backend (API REST)
│   ├── src/
│   │   ├── modules/
│   │   │   ├── auth/           # Autenticación y usuarios
│   │   │   ├── course/         # Cursos y gestión
│   │   │   ├── cart/           # Carrito de compras
│   │   │   ├── payments/       # Pagos y órdenes
│   │   │   ├── profiles/       # Perfiles de usuario
│   │   │   ├── admin/          # Panel de administración
│   │   │   └── ...
│   └── ...
├── front/       # Frontend (Next.js)
│   ├── app/
│   ├── components/
│   ├── context/
│   ├── hooks/
│   ├── helpers/
│   ├── services/
│   ├── types/
│   ├── validators/
│   └── ...
└── README.md
```

---

## ⚡ Instalación Rápida

```bash
# Clona el repositorio
git clone https://github.com/DiegoMarzioni/ProyectoFinal.git
cd ProyectoFinal

# Instala dependencias del backend
cd back
npm install

# Instala dependencias del frontend
cd ../front
npm install
```

---

## 🖥️ Ejecución

### Backend
```bash
cd back
npm start
# Servidor en http://localhost:3001
```

### Frontend
```bash
cd front
npm run dev
# App en http://localhost:3000
```

---

## 📦 Funcionalidades

- Autenticación de usuarios (registro, login, recuperación de contraseña)
- Catálogo de cursos por categorías
- Carrito de compras
- Checkout y gestión de órdenes
- Perfil de usuario y edición
- Panel de administración para gestión de usuarios y cursos
- Animaciones y diseño responsivo

---

## 👨‍💻 Autor

**Diego Marzioni**
**Laura Mussa**
**Jesus Anaya**
**Gonzalo Moreiro**
**Adan Franco**

---


##🚀 Instalación y ejecución

## Clonar el proyecto

git clone <REPO_URL>
cd devcore

## Frontend

cd frontend
npm install
npm run dev
# o yarn dev / pnpm dev


Abre http://localhost:3000
 en tu navegador.

## Backend

cd backend
npm install
npm run start:dev
# Producción: npm run start:prod

## Pruebas

npm run test      # Unitarias
npm run test:e2e  # End-to-end
npm run test:cov  # Cobertura

## 🌐 Despliegue

Frontend: recomendado en Vercel
Backend: desplegable en AWS/Mau usando NestJS Mau:


npm install -g @nestjs/mau
mau deploy


## 🔗 Proyecto destacado

Repositorio GitHub: [DevCore](https://github.com/DevCore-PF)

Plataforma educativa desarrollada con enfoque full stack, escalable y modular.

## 📚 Recursos

- [NestJS Docs](https://docs.nestjs.com/)  
- [Next.js Docs](https://nextjs.org/docs)  
- [TypeORM Docs](https://typeorm.io/)  
- [Tailwind CSS Docs](https://tailwindcss.com/docs)

## 📝 Licencia

MIT License – Proyecto Open Source
