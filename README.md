# 🚀 Portal TechNova Solutions

Portal institucional desenvolvido em **HTML5 semântico** para a empresa fictícia **TechNova Solutions**, especializada em Cloud Computing, Inteligência Artificial, Cibersegurança e Engenharia de Software.

---

## 📋 Sobre o Projeto

O objetivo deste projeto é estruturar uma landing page corporativa completa, acessível e otimizada para mecanismos de busca (SEO), apresentando os serviços, planos, equipe e conteúdos tecnológicos da empresa.

### ✨ Funcionalidades e Seções Implementadas

* **Cabeçalho Responsivo (`<header>`):** Logotipo com link para a home, campo de busca geral e menu sanduíche nativo utilizando as tags `<details>` e `<summary>` (sem dependência de JavaScript).
* **Seção Hero & Destaques (`#inicio`):** Chamada principal (CTA) para diagnóstico gratuito e vitrine visual (`<figure>` e `<figcaption>`) das principais soluções.
* **Sobre Nós & Equipe (`#sobre`):** História da empresa, pilares estratégicos (Missão, Visão e Valores) e apresentação dos líderes especialistas.
* **Catálogo de Serviços & Planos (`#servicos`):** Descrição das frentes de atuação e uma **tabela comparativa semântica** (`<table>`, `<thead>`, `<tbody>`, `<tfoot>`, `colspan` e `rowspan`) detalhando os planos *Start*, *Business* e *Enterprise*.
* **Blog & Central de Notícias (`#blog`):** Barra de pesquisa interna, navegação por categorias e cards de artigos técnicos com marcação de data (`<time>`).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica, acessível e preparada para SEO.

---

## 📂 Estrutura de Pastas Sugerida

```text
projeto-technova/
├── index.html          # Página principal do portal
├── README.md           # Documentação do projeto
└── img/                # Diretório de imagens do site
    ├── destaque-cloud.jpg
    ├── destaque-ia.jpg
    ├── destaque-dev.jpg
    ├── equipe1.jpg
    ├── equipe2.jpg
    ├── equipe3.jpg
    ├── blog1.jpg
    └── blog2.jpg
```

---

## ⚠️ Pontos de Atenção / Próximos Passos

Como o código atual está em desenvolvimento, alguns ajustes são recomendados para a finalização:

1. **Fechamento das tags finais:** O código atual é interrompido no segundo `<article>` do blog e fecha diretamente com `</head></html>`. É necessário concluir o artigo, adicionar a seção `#contato`, o `<footer>` e fechar corretamente as tags `</section>`, `</main>` e `</body>`.
2. **Atributo de idioma:** Alterar `<html lang="en">` para `<html lang="pt-BR">`, já que todo o conteúdo está em português.
3. **Link de Contato no Menu:** Corrigir o item `<li><a href="#contato"></a>Contato/Localização</li>` para que o texto fique dentro da tag `<a>`.
4. **Estilização (CSS):** Adicionar folhas de estilo para layout responsivo, tipografia e identidade visual.

---

## 🚀 Como Executar

1. Clone este repositório ou baixe os arquivos.
2. Certifique-se de que as imagens estejam dentro da pasta `img/` com os respectivos nomes.
3. Abra o arquivo `index.html` diretamente em qualquer navegador web.
