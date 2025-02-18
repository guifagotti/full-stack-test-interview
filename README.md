# ⚡ Desafio Rápido para Desenvolvedor Full Stack  

Este desafio foi criado para avaliar rapidamente suas habilidades como **desenvolvedor Full Stack**. Ele deve ser concluído em **até 30 minutos** e será realizado durante a entrevista.  

📌 **Importante:**  
❌ **O uso de IA para gerar código é proibido e resultará na desclassificação.**  
✅ **O objetivo é avaliar sua lógica, organização do código e capacidade de resolver problemas rapidamente.**  

---

## 🚀 O Desafio  

Você deve desenvolver uma pequena **API REST** e uma **interface web minimalista** para um **sistema de tarefas (To-Do List)**.  

### **1️⃣ Backend (API REST com Node.js e banco de dados em memória)**  

Crie uma **API REST** que permita a criação, listagem e remoção de tarefas.  

#### 🔹 **Requisitos**  
✔ Utilizar **Node.js com TypeScript**  
✔ Usar **Express.js** ou **Fastify** como framework web  
✔ Utilizar um **banco de dados em memória** (array ou SQLite)  
✔ Implementar **duas rotas principais**:  
   - `POST /tasks` → Criar uma nova tarefa  
   - `GET /tasks` → Listar todas as tarefas  
   - `DELETE /tasks/:id` → Remover uma tarefa  

#### 📝 **Modelo da Tarefa**  
```json
{
  "id": "uuid",
  "title": "Finalizar teste técnico",
  "completed": false
}
```

#### 🎯 **Diferenciais (ganhe pontos extras!)**  
✅ **Validação de entrada (ex: não permitir títulos vazios)**  
✅ **Utilização de UUIDs para identificação das tarefas**  
✅ **Implementação de um middleware para log de requisições**  

---

### **2️⃣ Frontend (Interface Web com Next.js)**  

Crie uma pequena **interface web** para interagir com a API, permitindo ao usuário **adicionar, visualizar e excluir tarefas**.  

#### 🔹 **Requisitos**  
✔ Utilizar **Next.js com TypeScript**  
✔ Criar uma única página (`/`) com:  
   - Um **campo de input** para digitar uma nova tarefa  
   - Um **botão para adicionar tarefas**  
   - Uma **lista de tarefas exibindo os itens cadastrados**  
   - Um **botão de excluir** ao lado de cada tarefa  

#### 🎯 **Diferenciais (ganhe pontos extras!)**  
✅ **Estado gerenciado corretamente (React hooks: useState, useEffect)**  
✅ **Chamadas à API bem estruturadas e tratadas (fetch ou Axios)**  
✅ **Estilização simples, mas agradável (TailwindCSS, Material UI ou CSS puro)**  

---

## 🕒 Tempo Estimado  

⏳ **30 minutos**  

Seja objetivo e eficiente. Lembre-se de priorizar um código **limpo, organizado e funcional**.  

Boa sorte! 🚀
