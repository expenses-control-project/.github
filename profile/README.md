<div align="center">
  <img width="200px" height="200px" src="https://github.com/expenses-control-project/app-cliente/blob/master/src/assets/img/logo_ec.svg"/>
  <h1 align="center">Expenses Control - Sistema de Gestión de Gastos</h1>
</div>

![ alt text ](https://img.shields.io/badge/Version-alpha0.0.0-28B463?style=for-the-badge)
![ alt text ](https://img.shields.io/badge/Vite-5.2.0-646CFF?style=for-the-badge&logo=Vite)
![ alt text ](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=React)
![ alt text ](https://img.shields.io/badge/Tailwindcss-3.4.3-0F172A?style=for-the-badge&logo=tailwindcss)
![ alt text ](https://img.shields.io/badge/Bootstrap-5.3.0-702ff3?style=for-the-badge&logo=Bootstrap)
![ alt text ](https://img.shields.io/badge/PostgreSQL-16.4.0-4479A1?style=for-the-badge&logo=postgresql)
![ alt text ](https://img.shields.io/badge/NestJS-10.3.10-ea295a?style=for-the-badge&logo=NestJS)
![ alt text ](https://img.shields.io/badge/pnpm-8.14.1-F69220?style=for-the-badge&logo=pnpm)


Expenses Control es un sistema de gestión de gastos intuitivo y de código abierto 💸

## Como desplegar el proyecto en Firebase 🔥
> Debemos tener instalado dos paquetes, primero firebase `firebase` dentro del proyecto. Comando: `pnpm i firebase`
> Y `firebase-tools` de manera global. Comando `pnpm i -D firebase-tools`

Antes que nada tendremos que iniciar sesión en nuestra cuenta de firebase dentro de nuestro dispositivo
```bash
firebase login
```

Primero creamos los archivos para producción por medio del siguiente comando 
```bash
pnpm run build
```

Luego tendremos que hacer el deploy del sistema en nuestro hosting en Firebase
```bash
firebase deploy
```
