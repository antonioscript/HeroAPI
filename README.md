# HeroAPI
API construída em Nest.JS para o cadastro de uma base geral de Super heróis

<p align="center">
  <img src="https://github.com/user-attachments/assets/648b7d33-d690-4b00-b01b-a42e24d6301b" alt="HeroAPI" width="500"/>
</p>

---

# Guia

## 1. Sobre o Nest.JS
https://docs.nestjs.com/

## 2. Instalar o Node e o NPM
https://nodejs.org/pt/download/prebuilt-installer

### Verificar a versão do Node
``` powershell
node --version
```

### Verificar a versão do NPM
``` powershell
npm--version
```

## 3.Criar o Projeto 
``` powershell
nest new HeroAPI
```


## 4.Executar a Aplicação
``` powershell
npm run start:dev
```

## 5.Prisma (ORM)
![prismapng](https://github.com/user-attachments/assets/f4834259-755e-411a-979b-57c8230a96e0)

https://docs.nestjs.com/recipes/prisma

### Instalar o Prisma
``` powershell
npx prisma init
```
### Criar Migração
``` powershell
npx prisma migrate dev
```

### 6.Criar os Módulos
https://www.canva.com/design/DAGMvbkSn34/xndrj2HETBwdmhntErOznw/edit

### Criação do Serviço
``` powershell
nest generate service heroes
```
### Criação do Controller
``` powershell
nest generate controller hero
```

### Criação do Módulo
``` powershell
nest generate module hero
```











