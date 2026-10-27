# Portfólio web — Erick Gomes

Este diretório `docs/` é o ponto de publicação de páginas estáticas do portfólio. A estrutura foi feita para comportar **vários projetos em um só site**, sem depender de Node.js, frameworks no servidor ou banco de dados para as demonstrações.

## Estrutura

```text
docs/
├── index.html                    # Vitrine dos trabalhos
└── barbearia-classe-a/
    └── index.html                # Prévia interativa da Barbearia Classe A
```

## Publicação com GitHub Pages

No GitHub, abra **Settings → Pages → Build and deployment** deste repositório. Em **Source**, escolha **Deploy from a branch**; selecione a branch **main** e a pasta **/docs**. Salve a configuração.

Após a implantação pelo GitHub Pages, os endereços esperados são:

- Portfólio: https://gmerick.github.io/Gmerick/
- Barbearia Classe A: https://gmerick.github.io/Gmerick/barbearia-classe-a/

Esses links só passam a funcionar **depois** que Pages estiver ativo e o deploy tiver concluído. O nome do repositório diferencia maiúsculas/minúsculas no caminho.

## Como acrescentar um novo projeto

1. Crie `docs/nome-do-projeto/index.html`.
2. Adicione um card apontando para `./nome-do-projeto/` na vitrine `docs/index.html`.
3. Registre os limites da demonstração e as tecnologias utilizadas.
4. Faça commit. A publicação do Pages, quando ativada, acompanha a atualização.

## Barbearia Classe A

A página contém a versão **demonstrativa e estática**, com navegação e simulação local da reserva e agenda administrativa. **Não processa agendamentos reais**, não possui login nem banco de dados. A aplicação full-stack, desenvolvida separadamente, requer implantação de servidor e configurações de produção antes de atender clientes.

## Imagens e tipografia

O site faz referência a fotografias externas de Pexels e fontes do Google Fonts. Caso a conexão com esses serviços falhe, alguns elementos visuais podem não carregar. Confira os termos de uso e disponibilidade de cada mídia antes de comercializar ou republicar.
