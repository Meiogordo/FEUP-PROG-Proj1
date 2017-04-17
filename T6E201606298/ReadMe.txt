Estado de desenvolvimento do trabalho:
- Todos os objetivos apresentados no enunciado foram concretizados com sucesso.

Melhorias implementadas:
- Foi implementado um menu mut�vel, que mostra op��es baseado no conte�do de Menu.txt e chama fun��es baseado no que for definido na fun��o callFunctions em main.cpp; (c�digo do menu em Menu.h e Menu.cpp, classe Menu)
- Foi implementado um detetor de modifica��es n�o gravadas - No caso de o utilizador n�o ter gravado as altera��es que fez aparece um aviso que interroga o utilizador se deseja continuar aquando do carregamento de informa��o de ficheiros ou da sa�da do programa;
- Foi criado um namespace com fun��es genericamente �teis para evitar redefini-las ou ter de ter um objeto de apoio com estas fun��es. Est�o definidas em Utilities.h e Utilities.cpp, dentro do namespace Utilities;
- O c�digo relativo � gest�o da empresa de autocarros foi colocado, para ser mais modular e organizado, dentro da classe BusManager, em BusManager.h e BusManager.cpp;
- Foi adicionada a op��o de iniciar o programa sem carregar ficheiros, estando a mem�ria interna do programa vazia, mas que poder� ser populada com as op��es de adicionar linha e de adicionar condutores.

Nota:
Junto foram enviados dois ficheiros .txt que foram os usados para testar todas as funcionalidades do programa (linhas_test.txt e condutores_test.txt).