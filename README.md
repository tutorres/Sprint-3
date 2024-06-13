# Sprint-3
Repositório para colocar documentos utilizados na produção do trabalho em grupo da materia "Trabalho interdiciplinar Front-End".
A aplicação utiliza localStorage para armazenar os dados dos grupos esportivos. Para testar diferentes cenários, configure o localStorage com os seguintes passos:

Para Inserir Dados Iniciais:

Abra o console do desenvolvedor do seu navegador (geralmente pressionando F12 e selecionando a aba "Console").

Insira o seguinte comando para adicionar grupos esportivos:

localStorage.setItem('grupos', JSON.stringify([
    { nome: "Calouros de CC", data: "22/05/2024 10:30", local: "Quadra 3", esporte: "Futebol", imagem: 1 },
    { nome: "Volei Matinal", data: "22/05/2024 10:30", local: "Quadra 3", esporte: "Volei", imagem: 2 },
    { nome: "Grupo 3", data: "23/05/2024 14:00", local: "Quadra 2", esporte: "Basquete", imagem: 3 },
    { nome: "Grupo 4", data: "24/05/2024 16:00", local: "Quadra 4", esporte: "Basquete", imagem: 2 }
]));

Isso adicionará quatro grupos esportivos ao localStorage.

Para Inserir Dados Vazios:

Se desejar testar o cenário sem grupos, insira o seguinte comando:

localStorage.setItem('grupos', JSON.stringify([]));

Recarregar a Página

Após configurar os dados desejados no localStorage, recarregue a página (F5) para que as alterações sejam aplicadas.

Testar as Funcionalidades

Verifique se os grupos esportivos são exibidos corretamente na página inicial.
Experimente clicar nos botões "Deletar" para remover um grupo e verifique se a lista é atualizada conforme esperado.
Verifique se a mensagem "Você ainda não criou nenhum grupo" é exibida quando não há grupos para mostrar.
Suporte e Contato
Se você encontrar qualquer problema ou tiver dúvidas durante o teste da aplicação, sinta-se à vontade para entrar em contato com [seu email ou nome de usuário do GitHub].
