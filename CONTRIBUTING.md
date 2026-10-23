# Como contribuir 🤝

Obrigado por querer ajudar! O **Readme Template** é uma coleção de modelos em Markdown, então qualquer pessoa pode contribuir, mesmo sem saber programar. Este guia explica o que aceitamos e como enviar sua contribuição.

Ficou com dúvida em algum ponto? [Abra uma issue](https://github.com/iuricode/readme-template/issues/new) e a gente conversa.

## O que você pode fazer

| Contribuição | Onde | Exemplo |
| --- | --- | --- |
| Novo modelo de perfil | [`perfil/`](perfil) | `exemplo-08.md` |
| Novo modelo de repositório | [`repositorio/`](repositorio) | `exemplo-02.md` |
| Novos badges | [`badges-shields/readme.md`](badges-shields/readme.md) | Uma tecnologia que ainda não está na lista |
| Novos cards ou temas | [`cards-status/readme.md`](cards-status/readme.md) | Um tema novo do GitHub readme stats |
| Formatações do GitHub | [`avancado/readme.md`](avancado/readme.md) | Uma sintaxe nova do Markdown |
| Correções | Qualquer arquivo | Link quebrado, imagem que não carrega, erro de português |

Antes de começar, procure nas [issues](https://github.com/iuricode/readme-template/issues) e nos [pull requests](https://github.com/iuricode/readme-template/pulls) para ver se alguém já está fazendo o mesmo.

## Passo a passo

1. Faça um **fork** deste repositório.
2. Clone o seu fork e crie uma branch para a sua alteração:

   ```bash
   git clone https://github.com/SEU-USUARIO/readme-template.git
   cd readme-template
   git checkout -b perfil-exemplo-08
   ```

3. Faça as alterações e confira a pré-visualização (veja o [checklist](#antes-de-abrir-o-pull-request)).
4. Faça o commit seguindo o [padrão de commits](#padrão-de-commits):

   ```bash
   git add .
   git commit -m "✨ feat: adicionar exemplo-08 de perfil"
   ```

5. Envie a branch para o seu fork:

   ```bash
   git push origin perfil-exemplo-08
   ```

6. Abra um **pull request** para a branch `main` deste repositório, explicando em poucas linhas o que foi adicionado ou corrigido. Se a mudança for visual, inclua um print.

Prefere a interface do GitHub? Veja como [criar um pull request](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

## Regras para os modelos

- **Nome e pasta:** use o próximo número livre da pasta, como `exemplo-08.md`. Cada pasta tem um único tipo de modelo.
- **Português:** escreva textos, títulos e comentários em português.
- **Marcadores de preenchimento:** use `{seu nome}` ou `SEU-USUARIO`. Fora de blocos de código, **não** use `<nome>`: o GitHub entende como tag HTML e o texto some na renderização.
- **Dados reais:** não coloque e-mail, telefone nem fotos de pessoas reais ou imagens com direitos autorais. Para exemplos de avatar, use `https://github.com/octocat.png`.
- **Imagens:** prefira arquivos na própria pasta ou fontes estáveis, como `raw.githubusercontent.com`, `github.com/USUARIO.png` e `img.shields.io`. Evite copiar links de imagens de sites de terceiros, porque eles saem do ar.
- **Acessibilidade:** toda imagem precisa de texto alternativo (`alt`) que descreva o que ela mostra.
- **Serviços externos:** se o modelo depende de um serviço, como o GitHub readme stats, confirme que ele está no ar antes de enviar.
- **Badges:** a imagem exibida e a URL copiável têm que ser idênticas. Se o ícone não aparecer, o nome do `logo=` não existe no [Simple Icons](https://simpleicons.org): troque por um válido ou remova o parâmetro.
- **Novo modelo:** adicione uma linha para ele na lista do [README](README.md).

## Padrão de commits

Escreva as mensagens em português, no formato `emoji tipo: descrição`:

```text
📚 docs: atualizar o README
✨ feat: adicionar exemplo-08 de perfil
🐛 fix: corrigir link quebrado nos badges
```

É uma recomendação, não uma exigência, mas facilita a revisão. Nosso guia completo está em [padrões de commits](https://github.com/iuricode/padroes-de-commits).

## Antes de abrir o pull request

- [ ] O arquivo renderiza corretamente na pré-visualização do GitHub.
- [ ] Todas as imagens carregam e todos os links funcionam.
- [ ] Não há dados pessoais nem conteúdo com direitos autorais.
- [ ] Textos e commits estão em português.
- [ ] Atualizei o README, se adicionei um modelo novo.
- [ ] O pull request trata de um único assunto.

## Reportando um problema

Encontrou um erro, um link quebrado ou um badge sem ícone? [Abra uma issue](https://github.com/iuricode/readme-template/issues/new) informando o arquivo, o que está errado e, se puder, um print.

## Licença das contribuições

Ao enviar uma contribuição, você concorda que ela seja distribuída sob a [licença MIT](LICENSE.md) do projeto.
