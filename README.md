# Desafio_Imersao_Alura02
# Café com Poesia

Este notebook combina geração de linguagem AI, análise de sentimentos e escolhas personalizadas para criar uma experiência envolvente chamada "Café com Poesia". Ele utiliza inteligência artificial para se conectar de forma criativa com os usuários, oferecendo conteúdo poético e sugestões relacionadas ao seu estado emocional.

## Detalhes do Código

### Células de Markdown

- **Link de Abertura no Colab:** Permite abrir diretamente o notebook no ambiente Google Colab.

### Células de Código

#### Importações Iniciais

- Importa o módulo `google.generativeai` e a biblioteca `random` para utilizar na geração de conteúdo e escolha aleatória de mensagens.

#### Configuração da API

- Importa funções do Colab para acesso a dados do usuário, recupera uma chave de API armazenada e configura o SDK de IA generativa do Google para utilização dessa chave.

#### Configurações do Modelo

- Define configurações para a geração de conteúdo (como número de candidatos e temperatura) e ajusta configurações de segurança. Instancia o modelo `gemini-1.0-pro` com essas configurações.

#### Funções de Geração de Conteúdo e Recomendações

- `generate_poetry`: Gera poesia com base no sentimento do usuário.
- `recommend_coffee`: Sugere um tipo de café baseado no sentimento do usuário.
- `get_message`: Oferece uma mensagem de apoio ou inspiração com base no sentimento.

#### Função Principal (`main`)

- Executa o programa principal que:
  - Solicita ao usuário que diga como está se sentindo.
  - Usa a entrada do usuário para gerar uma recomendação de café, uma poesia e uma mensagem de apoio ou inspiração.
  - Exibe todas essas informações formatadas de maneira amigável.

### Execução do Programa

#### Fluxo do Programa

- Ao executar, o programa interage com o usuário perguntando sobre seu estado emocional atual.
- Baseado na resposta, o programa gera uma recomendação de café, cria uma poesia e escolhe uma mensagem positiva para exibir ao usuário.
