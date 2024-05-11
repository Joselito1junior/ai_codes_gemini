Gerador de Formatação de Referências Bibliográficas com Google Gemini
---------------------------------------------------------------------

Este projeto utiliza o poder dos modelos de linguagem do Google Gemini para gerar automaticamente a formatação correta de referências bibliográficas, a partir de uma descrição textual da fonte.

**Funcionalidades:**

*   **Identificação do tipo de referência:** O sistema identifica o tipo de fonte (livro, artigo, website, etc.) a partir de uma descrição em linguagem natural.
    
*   **Formatação automática:** Gera a referência bibliográfica formatada de acordo com normas como ABNT, APA, etc.
    
*   **Exemplos e explicações:** Fornece exemplos de referências formatadas e explicações sobre as regras de formatação para cada tipo de fonte.
    

**Tecnologia:**

*   **Google Gemini:** Modelo de linguagem avançado utilizado para processamento de linguagem natural, embedding de texto e geração de texto.
    
*   **Pandas:** Biblioteca Python para manipulação e análise de dados.
    
*   **Numpy:** Biblioteca Python para computação numérica.
    
*   **Google Generative AI SDK:** Ferramentas para interagir com os modelos do Google Gemini.
    

**Como usar:**

1.  **Instalação:**
    

`   !pip install -q -U google-generativeai   `

1.  **Configuração:**
    
`   import google.generativeai as genai   `

`   GOOGLE_API_KEY="SUA_CHAVE_DE_API"     `

`   genai.configure(api_key=GOOGLE_API_KEY)   `

1.  **Executar o código:**
    

*   Defina a consulta descrevendo a fonte bibliográfica.
    
*   Execute a função prompt\_create(consulta)
    

**Exemplos de consultas:**

*   "Qual a forma de fazer uma referência bibliográfica de um livro escrito por apenas um autor?"
    
*   "Me dê um exemplo de referência bibliográfica de um texto estraido de uma tese de mestrado"
    
*   "Qual a forma o tipo de referência bibliográfica em 'SILVA, João. A importância da educação online: desafios e oportunidades. Disponível em: [https://www.educaca.com.br/importancia-educacao-online/](https://www.educacaoonline.com.br/importancia-educacao-online/). Acesso em: 10 de março de 2023.'"
    

**Contribuições:**

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, enviar pull requests ou sugerir novas funcionalidades.

**Limitações:**

*   O sistema está em desenvolvimento e pode conter imprecisões na formatação de referências.
    
*   A precisão da formatação depende da qualidade da descrição textual da fonte.
    

**Próximos passos:**

*   Implementar suporte para diferentes normas de formatação (ABNT, APA, etc.).
    
*   Aperfeiçoar a precisão do sistema através de treinamento com dados adicionais.
    
*   Criar uma interface gráfica intuitiva para facilitar o uso.
