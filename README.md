Para rodar o Ludo Clash no PyCharm, siga estes passos:

Instalar o Python e o Pygame
1.1. Certifique-se de ter o Python 3.7 ou superior instalado no sistema.
1.2. Abra o Terminal e execute:
pip install pygame

Criar um novo projeto no PyCharm
2.1. Abra o PyCharm.
2.2. Clique em “New Project” (Criar Novo Projeto).
2.3. Escolha a pasta onde deseja salvar o projeto e dê um nome, por exemplo, “LudoClash”.
2.4. Verifique se o interpretador (Python Interpreter) aponta para a versão instalada.
• Se desejar usar um ambiente virtual, crie-o neste momento e selecione-o no interpretador.

Adicionar o arquivo de código-fonte
3.1. No painel Project (lado esquerdo), clique com o botão direito sobre a pasta raiz do projeto.
3.2. Selecione “New → Python File” e dê como nome ludo_clash.py (ou outro nome de sua preferência).
3.3. Abra o arquivo recém-criado e cole o conteúdo completo do código do Ludo Clash (classes Game, Board, Player, Piece, Dice etc.).
3.4. Salve o arquivo (Ctrl+S ou Cmd+S).

Verificar dependências no PyCharm
4.1. Vá em File → Settings (Windows) ou PyCharm → Preferences (macOS).
4.2. Navegue até Project: LudoClash → Python Interpreter.
4.3. Confirme se o pacote pygame aparece na lista.
• Se não estiver instalado, clique no ícone “+” no canto superior direito, busque por “pygame” e instale-o.

Executar o jogo
5.1. No painel Project, localize o arquivo ludo_clash.py.
5.2. Clique com o botão direito sobre esse arquivo e selecione “Run 'ludo_clash'”.
5.3. O PyCharm abrirá a janela do jogo.
5.4. Na tela inicial, aparecerá o menu com o título “Ludo Clash” e o subtítulo “A3 – Unisul”.
• Clique em “2 Jogadores” ou “4 Jogadores” para iniciar uma partida.
5.5. No tabuleiro, clique no dado (canto inferior direito) para rolar.
5.6. Depois de rolar, clique em uma peça válida para movê-la.

Testar funcionalidades
6.1. Verifique se as regras estão funcionando corretamente:
- Tirar 6 para sair da base ou avançar 6 casas.
- Casas seguras não permitem captura.
- Capturas em casas normais retornam peões adversários à base.
- Entrada no caminho final após completar as 52 casas.
- Chegada ao home (centro) ao percorrer índices 52 a 58.
- Tirada de 6 dá direito a novo lançamento, se houver movimento possível.
- Primeiro a levar as quatro peças ao centro vence.

Caso precise depurar ou ajustar
7.1. Se aparecer algum erro, abra o console de execução no rodapé do PyCharm para ler a mensagem.
7.2. Verifique se faltou instalar o pygame ou se há algum erro de sintaxe no código.
7.3. Ajuste o interpretador e reinstale o pygame, se necessário.
