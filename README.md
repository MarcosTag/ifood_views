# 🍱Ifood Views - Squad 3

O **Ifoode Views** é um repositório que tem por objetivo a criação de views simulando o front-end do ifood (algumas páginas estáticas), apenas com **HTML** e **CSS**, sem fins lucrativos, com a única finalidade de praticar os conhecimentos de um 'squad' em Git e GitHub.

## 🛠️Divisão das atribuições:
<details><summary>Página de Login</summary>
<p>

   ├── 👨‍💻**Marcos Almeida**
   
  - Criar tela de login com campos de email e senha (sem lógica real);
  - Botão "Continuar" navega para tela "2 - Tela inicial com restaurantes";
  - Criar branch: feature/login;
  - Criar PR para "main"; e
  - Ter seu PR revisado pelo Membro 2

</p>
</details> 
<details><summary>Página de Restaurantes</summary>
<p>

   ├── 👨‍💻**Alessandro Almeida**
   
  - Criar tela com uma lista estática de restaurantes (textos e Imagens);
  - Ao clicar em um restaurante, abrir "3 - Tela de Detalhes de Restaurante";
  - Criar branch: feature/inicial_restaurantes;
  - Criar PR para "main"; e
  - Ter seu PR revisado pelo Membro 3

</p>
</details> 
<details><summary>Página de Detalhes de Restaurantes</summary>
<p>

   ├── 👨‍💻**André Araújo**
   
  - Criar tela com nome do restaurante e lista estática de produtos;
  - Ao clicar em cima de um produto abrir "1 - Tela de Login";
  - Criar branch: feature/detalhes_restaurante;
  - Criar PR para "main"; e
  - Ter seu PR revisado pelo Membro 1

</p>
</details> 

## 📁Estrutura do Projeto:
    ifood_views/
    │
    ├── assets/           
        ├── css/
            └── global.css                  # Organiza o css que pode ser reaproveitado por todos os membros do squad
            └── reset.css                   # Padroniza o css básico dos navegadores
            └── style.css                   # Centraliza todos os arquivos .css através de @imports
        ├── fonts/
            ├── ifood_rc_textos/
                └── stylesheet.css          # @font-face 'iFood RC Textos'
            ├── ifood_rc_títulos/
                └── stylesheet.css          # @font-face 'iFood RC Titulos'
        ├── img/
            
    ├── pages/    
        └── .gitkeep
        └── .login.html
        └── .pagina_de_restaurantes.html
        └── .pagina_de_detalhes_de_restaurantes.html

    └── index.html
    └── README.md

---
