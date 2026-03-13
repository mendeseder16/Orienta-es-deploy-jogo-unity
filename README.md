# Orienta-es-deploy-jogo-unity

Para publicar seu jogo de pirata criado no Unity em formato WebGL, siga este passo a passo:

# 1. Modificações no Jogo

Primeiro, faça as modificações que você deseja no jogo do Pirata. Aqui estão algumas sugestões de alterações:

- Mudança de Gráficos: Substitua sprites e backgrounds por novas imagens.
- Adicionar Novos Desafios: Introduza novos inimigos ou mecânicas.
- Adicionar Sons: Inclua música de fundo e efeitos sonoros.

Após fazer suas alterações, teste o jogo para garantir que tudo funcione conforme o esperado.

# 2. Preparar a Publicação

Para publicar seu jogo em WebGL, siga estas etapas:

# Configurações do Build

1. Abra o Unity e vá para `File` > `Build Settings`.
2. Selecione `WebGL` na lista de plataformas. Se não estiver selecionado, clique em `Switch Platform`.
3. Clique em `Player Settings` e ajuste as configurações conforme necessário:
   - Nome do Jogo: Altere o nome e outras informações relevantes do jogo.
   - Resolução e Presentation: Ajuste as configurações de resolução.

# Construir o Jogo

1. No menu `Build Settings`, clique em `Build`.
2. Escolha um diretório onde você deseja salvar os arquivos do build. Crie uma nova pasta chamada, por exemplo, `Build_WebGL`.
3. Clique em `Select Folder` para iniciar a construção.

# 3. Subir o Jogo para um Servidor

Para que seu jogo fique acessível online, você precisará de um local para hospedá-lo. Algumas opções gratuitas ou de baixo custo são:

- itch.io
- GitHub Pages
- Netlify

# Usando GitHub Pages

1. Crie um repositório no GitHub. Por exemplo, `PirateGameWebGL`.
2. Faça o push dos arquivos gerados na pasta `Build_WebGL` para o repositório.
3. No repositório do GitHub, vá para `Settings` > `Pages`.
4. Configure a branch `main` ou `gh-pages` para servir arquivos do diretório `/` ou o diretório onde seus arquivos estão localizados.
5. Após algumas horas, o link do seu jogo estará disponível nesse mesmo menu.

# 4. Adicionar Documentação

No seu repositório, crie um `README.md` com:

- Uma descrição do jogo.
- Instruções de como jogar.
- O link para o seu jogo publicado.

Exemplo de `README.md`:

```markdown
# Jogo do Pirata

Este é o meu jogo de pirata criado no Unity. Mudei alguns gráficos e adicionei novos desafios!

## Como Jogar

- Use as setas do teclado para mover o personagem.
- Clique para atacar inimigos.
- Colete tesouros.

## Jogar Online

Você pode jogar a versão WebGL [aqui](LINK_DO_JOGO).
```

# 5. Compartilhar com Outros

Depois de configurar tudo, compartilhe o link do seu repositório e informe sobre as alterações que você fez. Se precisar de mais ajuda em um ponto específico ou tiver dúvidas.
