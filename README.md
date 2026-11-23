# Gama Engenharia & Consultoria — site

Landing page da Gama Engenharia & Consultoria (Nossa Senhora do Socorro/SE).

Site estático: um `index.html` e as imagens em `assets/img/`. Não precisa de build, servidor nem banco de dados.

## Estrutura

```
index.html                  página completa (HTML + CSS + um pequeno script)
assets/img/
  logo-gama.svg             logo horizontal (fundo claro)
  logo-gama-negativo.svg    logo horizontal (fundo azul, rodapé)
  simbolo-gama.svg          símbolo 3D da abertura
  simbolo-marca-dagua.svg   marca-d'água da abertura
  favicon.svg               ícone da aba do navegador
  eri-gama.jpg              foto do Eri (seção "Quem somos")
```

## Publicar no GitHub Pages

1. Envie estes arquivos para um repositório no GitHub.
2. No repositório, abra **Settings › Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em alguns minutos o site fica no ar em `https://<usuario>.github.io/<repositorio>/`.

Para usar um domínio próprio (por exemplo, `www.seudominio.com.br`), informe-o em **Settings › Pages › Custom domain** e crie no registro do domínio um registro `CNAME` apontando para `<usuario>.github.io`.

## Formulário de contato

O formulário não precisa de servidor: ao clicar em **Enviar pedido**, ele abre o WhatsApp `(79) 99985-7711` com a mensagem já preenchida (nome, empresa, telefone, serviço e detalhes). Para trocar o número, edite `5579999857711` no `index.html` (aparece nos botões e no script no fim do arquivo).

## Pendências de conteúdo

Trechos entre colchetes no `index.html` precisam ser preenchidos antes de divulgar o site:

- Fotos e nomes das obras na seção **Projetos** (`[FOTO DO PROJETO]`, `[Nome da obra]`, `[Cidade/SE]`).
- História do Eri: início da carreira, marcos, ano de fundação da Gama e a frase dele.
- CNPJ no rodapé (`[SEU CNPJ]`).

## Identidade visual

Cores, fontes e regras de uso seguem o Manual da Marca Gama: azul `#0B1E46`, ouro `#C4994B`, fonte Inter (carregada do Google Fonts).
