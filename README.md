Resposta:
Quando se faz a atribuição do parâmetro newConfig ao this.config cria-se um novo objeto ao acessar a segunda classe.

Em geral, pode se acessar o Config ConfigResource pelo Swagget e assim alterando o formato do relatório, também o tipo de gráfico utilizando o PUT, porém, quando precisamos solicitar o GET ainda pelo ConfigResource ele confirma a mudança.

Ao solicitar o GET do RelatorioResource ele cria um novo objeto com os parâmetros iniciais, contrariando o padrão singleton.
