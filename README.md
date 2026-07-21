[![Demo](https://img.shields.io/badge/Demo-Online-000?style=for-the-badge&logo=vercel)](https://odonto-six.vercel.app/)

# Landing page odontológica

Landing page responsiva para centralizar os endereços e canais de contato de uma clínica odontológica. A página apresenta as unidades da clínica e oferece acesso direto à localização no Google Maps e ao atendimento pelo WhatsApp.

## Demonstração

Acesse a versão publicada do projeto:

👉 https://odonto-six.vercel.app/

## Tecnologias

- HTML5
- CSS3

O projeto não possui dependências, etapa de compilação ou servidor obrigatório.

## Como executar

Clone o repositório e abra o arquivo `index.html` no navegador:

```bash
git clone <URL_DO_REPOSITORIO>
cd "odonto lading page"
```

Como alternativa, utilize a extensão Live Server do VS Code para visualizar as alterações automaticamente durante o desenvolvimento.

## Estrutura

```text
.
├── imgs/
│   └── logo.png       # Logo exibida no cabeçalho
├── index.html         # Conteúdo e links da página
├── styles.css         # Estilos responsivos
├── LICENSE            # Licença MIT
└── README.md
```

## Personalização

No arquivo `index.html`, edite os dados de cada unidade:

- nome da clínica e da unidade;
- link de localização do Google Maps;
- link de contato do WhatsApp, no formato `https://wa.me/55DDDNUMERO`.

Para adicionar outra unidade, duplique o elemento `<article class="card">` dentro da seção com a classe `grid` e atualize as informações.

As cores, espaçamentos e tipografia podem ser ajustadas em `styles.css`, principalmente pelas variáveis declaradas em `:root`.

## Licença

Este projeto está sob a [licença MIT](LICENSE).