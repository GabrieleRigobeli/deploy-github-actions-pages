# 🚀 Deploy Automático com GitHub Actions + GitHub Pages

## 📌 Sobre o Projeto

Este projeto foi criado com o objetivo de praticar conceitos fundamentais de **DevOps**, utilizando **GitHub Actions** para automatizar o **deploy contínuo** de uma aplicação web estática no **GitHub Pages**.

A cada novo *push* na branch `main`, uma **pipeline automática** é executada, publicando a versão atualizada do site sem intervenção manual.

---

## ⚙️ Tecnologias Utilizadas

- HTML5  
- CSS3  
- Git e GitHub  
- GitHub Actions  
- GitHub Pages  
- CI/CD (Integração e Entrega Contínua)

---

## 🔄 Como Funciona a Pipeline (CI/CD)

1. Alterações são enviadas para a branch `main`
2. O **GitHub Actions** detecta o evento `push`
3. O workflow executa:
   - Checkout do repositório
   - Preparação do ambiente
   - Publicação automática no GitHub Pages
4. O site é atualizado automaticamente

📁 Workflow localizado em:
