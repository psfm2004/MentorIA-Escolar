# MentorIA Escolar 🤖🎓

Seu Mentor AI de Estudos para Ensino Médio!

MentorIA Escolar é um script Python interativo que utiliza a API Google Gemini para:
- Analisar boletins escolares em PDF.
- Estimar notas faltantes.
- Calcular a nota necessária na Prova Final para aprovação.
- Gerar planos de estudo semanais personalizados e empáticos.
- Exportar planos para Excel (.xlsx) e Google Calendar (.ics).

O objetivo é ajudar estudantes do Ensino Médio a entenderem melhor sua situação acadêmica, se organizarem e traçarem um caminho claro para alcançar seus objetivos, tudo com o apoio de uma inteligência artificial com um toque de "irmão mais velho".

## ✨ Funcionalidades Principais

*   **Análise Inteligente de Boletim:** Faça upload do seu boletim em PDF e deixe a IA extrair suas disciplinas e notas.
*   **Projeção de Notas para PF:** Descubra quanto você precisa tirar na Prova Final, com estimativas para outras notas faltantes.
*   **Plano de Estudos Personalizado:** Receba um cronograma semanal detalhado, focado nas suas prioridades e com sugestões de atividades, considerando sua disponibilidade.
*   **Disponibilidade Flexível:** Informe seus horários livres (ex: 18:00-20:30) para cada dia da semana.
*   **Tom Empático:** Interações e feedbacks pensados para serem acolhedores e motivadores.
*   **Exportação Fácil:** Leve seu plano de estudos para onde quiser (Excel ou Calendário).
*   **Agente de Currículo (BNCC):** Sugestões de tópicos da BNCC para revisão (em desenvolvimento/expansão).

## 🚀 Como Usar

1.  **Ambiente:** Este projeto foi desenvolvido para ser executado no Google Colab.
2.  **Configuração da API Key:**
    *   Obtenha uma API Key para a Google Gemini API (atualmente, modelos como `gemini-1.5-flash-latest`).
    *   No Google Colab, vá em "Segredos" (ícone de chave no painel esquerdo) e adicione um novo segredo chamado `GOOGLE_API_KEY` com o valor da sua chave. Certifique-se de que a opção "Acesso ao notebook" está marcada.
3.  **Instalação de Bibliotecas:** A primeira célula do notebook instala as dependências necessárias:
    ```python
    !pip install pandas openpyxl ics PyPDF2 google-generativeai -q
    ```
4.  **Execução:** Execute as células do notebook em ordem. Siga as instruções interativas no console de saída.
    *   Você precisará montar seu Google Drive para salvar e carregar dados de alunos entre sessões.
    *   Faça o upload do seu boletim em PDF quando solicitado.
    *   Informe sua disponibilidade de horários.

## 🛠️ Tecnologias Utilizadas

*   Python
*   Google Gemini API (via `google-generativeai`)
*   Pandas (para manipulação de dados e tabelas)
*   Openpyxl (para exportação para Excel)
*   ics (para exportação para Google Calendar)
*   PyPDF2 (para leitura inicial de texto de PDFs)
*   Google Colab (ambiente de execução)

## 🤝 Contribuições

Contribuições são bem-vindas! Se você tiver ideias para melhorias, novas funcionalidades ou correções de bugs:
1.  Faça um Fork do projeto.
2.  Crie uma nova Branch (`git checkout -b feature/sua-feature`).
3.  Faça commit das suas alterações (`git commit -m 'Adiciona sua-feature'`).
4.  Faça Push para a Branch (`git push origin feature/sua-feature`).
5.  Abra um Pull Request.

## 📝 Licença

Este projeto é distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
*(Se você adicionou uma licença, caso contrário, remova esta linha ou adicione uma licença depois)*

---

*Diga adeus à confusão com as notas e olá para um estudo mais inteligente e organizado com o MentorIA Escolar!*
