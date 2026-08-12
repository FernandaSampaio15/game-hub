# 📌 game-hub

> API RESTful para uma plataforma social de jogos inspirada no Letterboxd, permitindo registrar, avaliar e compartilhar experiências com games.

---

## 🚀 Sobre o Projeto

O projeto é uma plataforma social voltada para gamers buscarem informações sobre jogos, organizarem seu catálogo pessoal (jogados, jogando, lista de desejos) e interagirem através de avaliações e resenhas. A aplicação consome **APIs externas** de dados de games para manter o acervo sempre atualizado.

---

## ✨ Funcionalidades

- [x] **Catálogo de Games:** Busca e exibição de detalhes sobre jogos consumidos de API externa (ex: RAWG / IGDB).
- [x] **Diário & Diário de Jogos (*Logs*):** Registro de jogos concluídos, datas e horas jogadas.
- [x] **Avaliações e Resenhas:** Criação de reviews e atribuição de notas/estrelas.
- [x] **Listas Personalizadas:** Criação de listas de jogos favoritos, *backlog* e lista de desejos (*wishlist*).
- [x] **Perfil Social:** Acompanhamento de atividades e histórico de jogos de outros usuários.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Java
- **Framework:** Spring Boot
- **Banco de Dados:** PostgreSQL
- **Integração:** Consumo de REST APIs Externas (OpenFeign / RestTemplate / WebClient)
- **Containerização:** Docker & Docker Compose
- **Arquitetura:** API RESTful

---

## 🧰 Como Executar o Projeto

```bash
# Clone o repositório
git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)

# Suba os containers com rebuild automático das imagens
docker-compose up -d --build
