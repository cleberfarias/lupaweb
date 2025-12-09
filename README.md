# LupaWeb

Site do projeto Lupa — sistema desenvolvido na Faculdade UniSenai para centralizar o registro e a busca de objetos perdidos no campus.

Visão geral
- O LupaWeb facilita o registro e a localização de itens perdidos/encontrados no campus.
- Objetivo: reduzir perda de tempo e melhorar a chance de devolução de objetos aos seus donos.

Demo
- Versão publicada: https://lupaweb-delta.vercel.app

Funcionalidades
- Cadastro de objetos perdidos/encontrados (título, descrição, local, data, contato).
- Pesquisa e filtragem por descrição, local e data.
- Listagem dos objetos recentes.
- Interface responsiva — funciona em desktop e mobile.

Tecnologias
- Frontend: HTML, CSS, JavaScript (projeto estático).
- Deploy: Vercel (site já publicado), pode ser hospedado em qualquer serviço para sites estáticos.

Instalação e execução local
1. Clone o repositório:
   git clone https://github.com/cleberfarias/lupaweb.git
2. Entre na pasta do projeto:
   cd lupaweb
3. Abra `index.html` no navegador ou sirva com um servidor local:
   - Com npx serve:
     npx serve .
   - Ou usando Python 3:
     python3 -m http.server 8000
   - Depois abra: http://localhost:8000

Estrutura (exemplo)
- index.html — página principal
- css/ — estilos
- js/ — scripts
- assets/ — imagens e outros recursos

Boas práticas de uso
- Ao cadastrar um objeto, inclua o máximo de detalhes (descrição detalhada, local exato, data e contato) para aumentar a chance de identificação.
- Remova ou marque como devolvido quando o objeto voltar ao dono.

Contribuindo
1. Abra uma issue descrevendo a sugestão ou bug.
2. Faça um fork do projeto.
3. Crie uma branch para sua alteração:
   git checkout -b feat/nova-funcionalidade
4. Faça commits concisos e descritivos.
5. Abra um Pull Request para a branch `main` do repositório original, descrevendo o que foi alterado e por quê.
6. Inclua screenshots ou passos para verificar a mudança quando aplicável.
