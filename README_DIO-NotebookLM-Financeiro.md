# DIO-NotebookLM-Financeiro
Desafio DIO de desenvolver um NotebookLM com fontes abertas sobre assuntos financeiros.

## Fontes
- De onde vieram:
  - Inicialmente, utilizei vídeos de Economia básica do canal de YouTube Khan Academy, porém achei necessário livros sobre o assunto. Durante a pesquisa escolhi livros da OpenStax e CORE Project já que ambos os livros tem bastante fundamentação teorica. Por último procurei sobre informações financeiras em geral e especificas ao Brasil, para uma visão geral utilizei novamente um livro da OpenStax e para o mundo Financeiro do Brasil utilizei livros da FEBRABAN e CVM.
- Links:
  - [Livros CVM](https://www.gov.br/investidor/pt-br/educacional/publicacoes-educacionais/livros-cvm#:~:text=5.%20...%202025.%20TOP%20Planejamento%20Financeiro%20Pessoal.,hist%C3%B3ria%20da%20CVM%20pelo%20olhar%20de%20seus)
  - [Livros FEBRABAN](meubolsoemdia.com.br/e-books)
  - [CORE-Econ](http://core-econ.org/)
  - [OpenStax](https://openstax.org/subjects/business)
  - [Khan Academy](https://www.youtube.com/@khanacademy)
 
## Prompts
- Dei inicio ao NotebookLM, após adicionar todas as fontes encontradas e selecionadas, pedindo para que ele gerasse Resumo dos materiais em tópicos relevantes e também um guia de estudos.
- A primeira geração dos tópicos acabou sendo muito curta, apenas 4 assuntos, criei um prompt para que o NotebookLM gerasse mais tópicos, resultando em 6, o que eu achei suficiente para um assunto introdutório.
- Com um prompt eu perguntei das capacidades de gerar Slides para estudos, para que cada tópico tivesse um Slide único, para concentração de informação apropriada. Depois que ele gerou o primeiro slide, pedi uma suavizada na arte dos slides, pois era muito forte, distraindo do conteúdo.
- Por fim pedi para que ele gerasse um Glossário e 3 quizes sobre cada um dos tópicos com dificuldades variantes, para realmente testar os conhecimentos gerados pelo Notebook.
- Cada Quiz também foi necessário um prompt único, para que cada tópico pudesse ser investigado e o conhecimento testado devidamente.


## Prompts Reutilizáveis:
```Por favor expanda sobre o Tópico (x)```
```Gere mais um quiz de dificuldade (Básico/Intermediário/Avançado) sobre Tópico (x)```


## Link do NotebookLM
[Intro-Econ-Notebook](https://notebooklm.google.com/notebook/618e50ba-017d-4800-a941-2eb0d0e9cb45)
