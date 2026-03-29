# 🔐 Laboratório de Brute Force - Bootcamp Cybersecurity (DIO + Riachuelo)

## 📌 Descrição
Este repositório documenta as atividades práticas realizadas durante o módulo de **Brute Force Attacks** no bootcamp de Cybersecurity promovido pela DIO em parceria com a Riachuelo.

O foco deste laboratório foi compreender, na prática, como ataques de força bruta funcionam, suas variações e como ferramentas amplamente utilizadas podem explorar falhas de autenticação em sistemas vulneráveis.

---

## 🎯 Objetivos do Laboratório
- Entender o conceito de ataques de força bruta
- Simular cenários reais de ataque
- Utilizar ferramentas ofensivas para testes de autenticação
- Praticar técnicas como:
  - Password Spraying
  - Credential Stuffing
- Explorar serviços vulneráveis em ambiente controlado

---

## 🖥️ Ambiente Utilizado
- **Sistema Operacional:** Kali Linux  
- **Máquina Alvo:** Metasploitable 2  
- **Ambiente:** Laboratório isolado (rede local)

---

## 🧰 Ferramentas Utilizadas

### 🔹 Ataques de Força Bruta
- Medusa
- Hydra
- Ncrack

### 🔹 Testes em Aplicações Web
- Wpscan
- Patator

### 🔹 Quebra de Senhas
- John the Ripper

---

## 🔍 Técnicas Exploradas

### 🔸 Brute Force Tradicional
Tentativa exaustiva de combinações de usuário e senha até encontrar credenciais válidas.

### 🔸 Password Spraying
Uso de uma mesma senha comum contra múltiplos usuários para evitar bloqueios de conta.

### 🔸 Credential Stuffing
Utilização de credenciais previamente vazadas para tentar acesso em outros sistemas.

---

## 🧪 Atividades Realizadas

### ✔️ Criação de Wordlists
- Geração de listas personalizadas de senhas
- Uso de padrões comuns e variações

### ✔️ Ataques em Serviços
- SSH
- FTP
- SMB
- Formulários HTTP

### ✔️ Enumeração SMB
- Identificação de usuários
- Descoberta de compartilhamentos

### ✔️ Ataques a Arquivos Protegidos
- Quebra de senha de arquivos compactados (ZIP, etc.)

### ✔️ Testes em Formulários Web
- Automação de tentativas de login
- Identificação de falhas de autenticação

---

## ⚠️ Considerações de Segurança

Todos os testes foram realizados em ambiente controlado, com máquinas vulneráveis configuradas para fins educacionais.

> ❗ O uso dessas técnicas sem autorização é ilegal.

---

## 🛡️ Mitigações e Boas Práticas

- Implementação de políticas de senha forte
- Uso de MFA (Autenticação Multifator)
- Bloqueio após múltiplas tentativas de login
- Monitoramento de logs
- Implementação de CAPTCHA
- Rate limiting em serviços de autenticação

---

## 📚 Aprendizados

- Importância de credenciais seguras
- Velocidade de exploração com ferramentas automatizadas
- Impacto de vazamentos de credenciais
- Necessidade de múltiplas camadas de segurança

---

## 🚀 Conclusão

O laboratório proporcionou uma visão prática sobre ataques de força bruta e reforçou a importância de proteger sistemas contra esse tipo de ameaça.

---

## 👨‍💻 Autor
**Thiago Valentim**  
Bootcamp Cybersecurity - DIO + Riachuelo
