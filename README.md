# Seja bem vindo ao ME < CODE >

> Processo de seleção para estágio FrontEnd 

Este repositório contem informações sobre o processo de seleção, e será atualizado a cada etapa, seguindo as datas combinadas.

# O Projeto

🎯 O objetivo deste projeto é criar um app FullStack onde vamos criar um banco de talentos para futuros estagiários.

Para isso precisamos criar um site/plataforma/sistema por onde o interessado se inscreva no banco de talentos, e possa fazer o seu cadastro, recebendo no seu email nossos proximos testes.

👉 Ao final do processo de seleção, o projeto será publicado para utilização real.

É importante pra nós que todos se divirtam 😄 e aprendam 📚 enquanto estejam no processo conosco. 

# O Processo

O processo acontecerá em 3 ou 4 etapas, com dificuldade crescente, para encontrarmos aqueles estudantes mais animados, interessados e corajosos.

Ao final de cada etapa atualizaremos aqui o repositório com as orientações para próxima etapa!


# 1ª Etapa - Bootstraping

Nesta etapa queremos criar o projeto básico, o mínimo necessário para sairmos do zero.

**Início: 21/10/2022 - envio dos projetos: até 27/10/2022 - resultado: 28/10/2022**   

Tarefas da etapa:   
- Criar projeto frontend seguindo as instruções abaixo
- Criar repositório para seu projeto no github
- Deixar no readme apenas a informação sobre seu projeto
- Nos enviar a url do seu repositório por whatsapp: [este link](https://wa.link/zx8nma) para que possamos avaliar o que foi feito


## Frontend

- Criar projeto usando Next.js
- Na rota inicial, exibir com `<H1>` com "Usuários do banco de talentos"
- Instalar pacote AXIOS no projeto
- Ao renderizar a interface (apenas uma vez) fazer uma chamada get para [https://backendtalentos.herokuapp.com/listuser](https://backendtalentos.herokuapp.com/listuser) e obter a resposta, que será uma lista de usuários, exibindo seu login, senha, email e tenant
- Após receber esse array, você deve organizar esses usuários em forma de lista, a lista deve ser ordenada inicialmente pelo Id do usuário, e não deve conter o campo senha!