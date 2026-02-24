# 📅 Gerador de Cronograma Acadêmico Pro

O **Gerador de Cronograma Acadêmico** é uma ferramenta web simples e poderosa para criar calendários de aulas personalizados. Ele permite configurar carga horária, datas de início e fim, horários de aula, intervalos e feriados, gerando um PDF otimizado para impressão com design de alto contraste.

![GitHub license](https://img.shields.io/github/license/seu-usuario/seu-repositorio)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=flat&logo=javascript&logoColor=black)

## ✨ Funcionalidades

-   **Configuração Flexível:** Defina o título do curso, carga horária total e período (início/fim).
-   **Dias de Aula:** Seleção intuitiva dos dias da semana em que ocorrem as aulas.
-   **Gestão de Intervalos:** Adicione múltiplos intervalos (ex: almoço, café) com nomes e horários personalizados.
-   **Controle de Feriados:** Insira datas específicas para serem marcadas como feriado no calendário.
-   **Visualização em Tempo Real:** Gere uma prévia do calendário antes de exportar.
-   **Otimização para Impressão:** -   Design de alto contraste (bordas sólidas e texto preto nítido).
    -   Layout inteligente: evita quebras de página no meio de um mês.
    -   Fluxo contínuo: remove páginas em branco desnecessárias.

## 🚀 Como usar

1.  Abra o ficheiro `index.html` em qualquer navegador moderno.
2.  Preencha os dados do curso na área de configuração.
3.  Clique em **"1. Gerar Visualização"** para conferir o layout.
4.  Clique em **"2. Baixar PDF"** para salvar o documento pronto para imprimir.

## 🛠️ Tecnologias Utilizadas

-   **HTML5/CSS3:** Estrutura e estilização com foco em impressão (Media Queries).
-   **JavaScript (Vanilla):** Lógica de geração de datas e cálculos de calendário.
-   **[html2pdf.js](https://ekoopmans.github.io/html2pdf.js/):** Biblioteca para converter o conteúdo HTML em documentos PDF de alta qualidade.

## 📄 Layout do PDF

O documento gerado inclui:
-   **Card de Resumo:** Título do curso, carga horária total e cálculo automático de 75% de frequência mínima.
-   **Calendários Mensais:** Visualização clara com marcação diferenciada para dias de aula, intervalos e feriados.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

1.  Faça um Fork do projeto
2.  Crie uma Branch para sua funcionalidade (`git checkout -b feature/NovaFuncionalidade`)
3.  Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4.  Push para a Branch (`git push origin feature/NovaFuncionalidade`)
5.  Abra um Pull Request

---
Desenvolvido para facilitar a organização de professores e instituições de ensino.
