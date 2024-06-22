# Gerando um artigo técnico com ajuda da IA

Este é um projeto criado para o bootcamp "Fundamentos de IA para Devs", organizado pelo **Banco Santander** e a escola **DIO**.

O tema **UML para desenvolver aplicativos** foi desenvolvido da forma mais simples possível, porém incluindo até 9 diagramas UML.

Os conceitos foram aplicados para um caso prático : desenvolver um aplicativo para Escritórios de Advocacia.

# Ferramentas

As principais ferramentas utilizadas para produzir o e-book :

- [ChatGPT](https://chatgpt.com/): para gerar o roteiro do artigo e o código PLANTUML.
- [Copilot](https://copilot.microsoft.com/): para gerar a imagem da capa.
- [Visual Studio Code](https://code.visualstudio.com/): para ler o código PLANTUML e gerar os diagramas UML.

# Validação do conteúdo

 - [X] Todo o conteúdo gerado foi verificado, ajustado e reorganizado por mim. 
 - [X] Foi utilizado como base teórica o livro **"UML Essencial"** do autor **Martin Fowler**.


# Prompts utilizados

Foram executados os seguintes Prompts no ChatGTP, de forma sequencial, para ir construindo o roteiro e o conteúdo do artigo.

 - [X] Prompt 1 : 
 
    ***Atuar como engenheiro de software.*** 
    .
    *Preciso gerar diversos diagramas UML para meu projeto de criação de um aplicativo, segundo os detalhes abaixo. Forneça o código em linguagem PlantUML para cada diagrama UML. O codigo deve ser o mais detalhado posível.*
    . 
    ***Tópico :*** *criar um aplicativo para escritórios de advocacía.*
    . 
    ***Descrição :*** *Desenvolver os seguintes ítens :*
    .
    *- Requisitos funcionais : Cadastro de clientes; Cadastro de casos; Controle de agenda; Pesquisa, recuperação e geração de documentos com templates; Relatório de atividades; Indicadores de performance dos advogados; Controle de acesso e permissões segundo os perfis (administrador, suporte, advogado, cliente).*
    *- Integrações : Enviar as notificações por Gmail; Integrar a agenda com o calendário de Windows.*
    .
    *Gerar os diagramas de Casos de Uso , em linguagem PlantUML, para cada um dos requisitos funcionais e integrações.*

 - [X] Prompt 2 :

    ***Baseado nessa informação, gerar UM diagrama de Atividade, em linguagem PlantUML, envolvendo todos os requisitos funcionais***
    .
     ***Baseado nessa informação, gerar UM diagrama de Casos de Uso, em linguagem PlantUML, envolvendo todos os requisitos funcionais***
     .
     ***Baseado nessa informação, gerar UM diagrama de Sequência, em linguagem PlantUML, envolvendo todos os requisitos funcionais***
     .
     ***Baseado nessa informação, gerar UM diagrama de Transição de Estados, em linguagem PlantUML, envolvendo todos os requisitos funcionais***
     .
     ***Baseado nessa informação, gerar UM diagrama de Colaboração, em linguagem PlantUML, envolvendo todos os requisitos funcionais***
      .
     ***Baseado nessa informação, gerar UM diagrama de Visão geral de Interação, em linguagem PlantUML, envolvendo todos os requisitos funcionais***
     .
     ***Baseado nessa informação, gerar UM diagrama de Classes, em linguagem PlantUML, envolvendo todos os requisitos funcionais***
     .
     ***Baseado nessa informação, gerar UM diagrama de Componentes, em linguagem PlantUML, envolvendo todos os requisitos funcionais***   
     .
     ***Baseado nessa informação, gerar UM diagrama de Perfil, em linguagem PlantUML, envolvendo todos os requisitos funcionais***   

 - [X] Prompt 3 : 

    ***Escrever um artigo técnico baseado nos dados gerados, para publicar num site de tecnologia. Incluir os tópicos : introdução, definições importantes, descrições dos principais diagramas uml gerados, conclusão.***

Para gerar a imagem da capa, foram executados os seguintes prompts no COPILOT.

 - [X] Prompt 1 : 
 
    ***Gerar uma imagem cinematográfica  de um escritório de engenharia de software mostrando uma mesa com varios computadores e notebooks projetando hologramas de diagramas de fluxo de dados com o título "UML"*** 
    
 - [X] Prompt 2 :

    ***Faça os hologramas parecerem realistas!***

 - [X] Prompt 3 :

    ***Incluir um quadro branco na parede com post-it coloridos e com a frase escrita : UML***

Resultado : 

<img src="/titulo uml 4.jpeg">

# Gerar os diagramas UML

A partir do código em linguagem PLANTUML (gerado pelo ChatGPT), utilizamos o Visual Studio Code configurado com o PlugIn necessário.

<img src="/VSCode PlantUML.png">

