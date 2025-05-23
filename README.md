# Chatbot Educacional Interativo com Google Gemini e ADK

📚 Visão Geral: 
Este projeto é um chatbot educacional interativo desenvolvido para auxiliar estudantes do ensino fundamental e médio no aprendizado. Ele utiliza a inteligência artificial do Google Gemini e o Google Agent Developer Kit (ADK) para criar um sistema de agentes colaborativos que guiam os alunos na construção do conhecimento, fornecendo feedback, gerenciando contexto e buscando informações de fontes confiáveis.

🎯Objetivos Principais:
* Aprendizado Ativo: Incentivar o pensamento crítico através de perguntas guiadas, em vez de apenas fornecer respostas prontas.
* Curadoria de Conteúdo: Sugerir materiais de estudo relevantes e de fontes confiáveis, utilizando a busca do Google.
* Feedback Personalizado: Oferecer retorno sobre as respostas do estudante e adaptar a estratégia de ensino.
* Gerenciamento de Fontes: Permitir que os usuários adicionem e gerenciem uma lista de fontes de pesquisa consideradas confiáveis.

✨Funcionalidades:
O chatbot é composto por uma orquestração de diferentes agentes, cada um com uma função específica:

* Agente de Boas-Vindas: Inicia a interação de forma amigável, explicando o propósito do chatbot.
* Agente de Questionamento Guiado: Formula perguntas de acompanhamento para estimular o pensamento crítico e aprofundar o aprendizado.
* Agente de Busca e Validação de Fontes: Realiza pesquisas e avalia a credibilidade das fontes, priorizando as confiáveis.
* Agente de Contexto e Memória de Sessão: Mantém e formata o histórico da conversa para que os outros agentes tenham contexto.
* Agente de Curadoria e Sugestão de Conteúdo: Sugere conteúdo educacional relevante com base no tópico, nível do estudante e fontes confiáveis.
* Agente de Apresentação e Formatação de Texto: Formata e exibe as respostas do chatbot de forma clara e legível (em Markdown).
* Agente de Feedback e Adaptação: Analisa as respostas do estudante, fornece feedback e sugere adaptações na estratégia de aprendizado.
* Agente Anexador de Fontes Interativas: Permite aos usuários gerenciar a lista de fontes confiáveis através de comandos como /adicionar_fonte, /remover_fonte e /listar_fontes.
  
⚙️Como Configurar e Executar
Este projeto é ideal para ser executado em um ambiente Google Colab ou Jupyter Notebook.

** Pré-requisitos **
Conta Google (para acesso ao Google Colab).
Uma chave de API do Google Gemini.

** Passos para Configuração **
Obtenha sua Chave de API do Google Gemini:
Acesse o Google AI Studio: https://aistudio.google.com/
Crie uma nova chave de API.
No Google Colab, vá em Secrets (ícone de chave no menu lateral esquerdo) e adicione uma nova chave com o nome GOOGLE_API_KEY e o valor da sua chave de API.

** Abra o Notebook no Google Colab: **
Faça o upload do arquivo projetocompleto_sabrinadasilva_imersão_alura (1).py para o seu Google Drive.
Abra-o com o Google Colab.

** Execute as Células do Notebook: **
Comece executando a primeira célula (instalação de bibliotecas e configuração da API Key).
Prossiga executando cada célula na ordem, definindo as funções auxiliares e cada um dos agentes.
A última célula contém o FLUXO DOS AGENTES (main function). Execute-a para iniciar o chatbot.

** Interagindo com o Chatbot **
Após executar todas as células, o chatbot será iniciado e você poderá interagir com ele através do prompt de entrada:
Faça Perguntas: Digite sua pergunta sobre qualquer tema do ensino fundamental ou médio. O chatbot tentará guiá-lo no aprendizado ou buscar conteúdo.

** Gerencie Fontes: **
/adicionar_fonte <URL>: Adiciona uma nova fonte confiável (ex: /adicionar_fonte https://www.scielo.br/).
/remover_fonte <URL>: Remove uma fonte da lista.
/listar_fontes: Exibe todas as fontes confiáveis configuradas.

** Encerrar: ** Digite sair, fim ou adeus para finalizar a conversa.

🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para:
* Abrir issues para relatar bugs ou sugerir melhorias.
* Criar pull requests com novas funcionalidades ou correções.
