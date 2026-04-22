# una-blazor-lista12.
## 👤 Identificação
Integrantes :
•Letícia Petrina Machado Silva ,
•João Augusto Miranda Viana de Souza,
•Luana Xavier Monteiro,
•Pedro Morais Hilbert ,
- Daniel de Almeida Vieira ,
Curso: Ciência da Computação,
Disciplina: Interação Humano Computador e UX  ,
Professor: Daniel Henrique Matos de Paiva.




Certifique-se de ter o .NET SDK instalado.
Abra o terminal e clone este repositório.
Navegue até a pasta raiz do projeto (onde está o arquivo .csproj).
Execute o seguinte comando no terminal para iniciar a aplicação com: dotnet run..
Heurísticas de Nielsen Aplicadas

1. Visibilidade do Status do Sistema
O sistema informa o tempo todo o usuário sobre o que está acontecendo no programa através da atualização em tempo real do contador de pontos e da barra de progresso no canto inferior da tela.

2. Feedback Imediato
Ao clicar no botão "Registrar Ação", o usuário recebe resposta automática com o aumento dos pontos e atualização.

3. Consistência e Padrões
Todos os componentes seguem o mesmo padrão visual e de interação, facilitando o entendimento do usuário e tornando mais dinâmico.



Uso dos Parameter

 O parâmetro permite definir quantos pontos cada ação adiciona ao código, possibilitando reutilizar diversas vezes os mesmos componente com comportamentos diferentes, tornando mais ágil e flexível a criação do código.

O estado do componente é controlado por uma variável.

private int Total = 0;

A cada clique no botão, o método Incrementar() é chamado, atualizando o estado que é refletindo automaticamente na interface pelo sistema reativo do Blazor.










private int Total = 0;

A cada clique no botão, o método Incrementar() é chamado, atualizando o estado que é refletindo automaticamente na interface pelo sistema reativo do Blazor.
