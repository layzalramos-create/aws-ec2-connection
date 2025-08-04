# Conectando à instância EC2 via PuTTY no Windows

## ☁️ Requisitos
- Instância EC2 rodando na AWS
- Chave `.pem` baixada ao criar a instância
- PuTTY e PuTTYgen instalados

---

## 🧩 Etapas realizadas

### 1. Converter `.pem` em `.ppk`
- Abrir o **PuTTYgen**
- Clicar em **Load** e abrir a chave `.pem`
- Clicar em **Save private key**
- Salvar como `minha-chave.ppk`

---

### 2. Conectar com PuTTY
- Abrir o **PuTTY**
- Em **Host Name**: `ec2-user@SEU-IP-PÚBLICO`
- Ir em `Connection > SSH > Auth`
- Selecionar a chave `.ppk`
- Clicar em **Open**

---

### ✅ Resultado esperado
Você verá algo assim no terminal:
