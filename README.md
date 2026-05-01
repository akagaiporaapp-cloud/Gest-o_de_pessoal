📋 README - Sistema de Gestão Integrada CDD Itu

Sobre o Projeto

O Sistema de Gestão Integrada CDD Itu é uma aplicação web desenvolvida para gerenciar operações diárias de um Centro de Distribuição. O sistema permite o registro de ponto, ausências, ocorrências, controle de carga e publicação de avisos, integrando todos os dados diretamente com o Google Sheets para fácil acompanhamento e análise.

📱 Funcionalidades

1. Registro de Ponto

· Marcação de presença dos colaboradores
· Opções: Presente, Férias, AM (Atestado Médico), LM (Licença Médica), Folga, Serviço Externo
· Registro com data e hora automática

2. Ausências Programadas

· Planejamento de férias, folgas, licenças e ausências particulares
· Definição de período de início e fim
· Controle de equipe para melhor distribuição de tarefas

3. Ocorrências Gerais

· Registro de eventos operacionais importantes
· Motivos: Atraso LTR, Sedex 2º carga, Diversos
· Campo para detalhamento e número CIE opcional

4. Controle de Carga

· Registro de qualificados distribuídos
· Quantificação de volumes ou colaboradores alocados
· Acompanhamento da produtividade operacional

5. Quadro de Avisos

· Publicação de comunicados importantes
· Sistema de prioridades (Alta, Média, Baixa)
· Definição de prazo de validade para cada aviso

👥 Colaboradores

O sistema conta com 41 colaboradores cadastrados, distribuídos nas seguintes funções:

· Ciclistas
· Motociclistas
· Motoristas
· Pedestres
· Internos
· Gestão

🛠️ Tecnologias Utilizadas

· HTML5 - Estrutura da aplicação
· CSS3 - Estilização e design responsivo
· JavaScript (ES6+) - Lógica e interatividade
· Font Awesome 6 - Ícones
· Google Fonts (Inter) - Tipografia
· Google Apps Script - Backend e integração com planilhas

📊 Integração com Google Sheets

Todos os dados são enviados para uma planilha do Google Sheets através de um script Apps Script. O sistema envia as informações para as seguintes abas:

· Ponto - Registros de ponto dos colaboradores
· Ausencias - Planejamento de ausências
· Ocorrencias - Registro de ocorrências operacionais
· Carga - Controle de carga e distribuição
· Avisos - Publicações do quadro de avisos

🚀 Como Usar

Acesso Direto

O sistema é uma aplicação web que pode ser hospedada em qualquer servidor web ou até mesmo executada localmente.

1. Baixe os arquivos do sistema
2. Abra o arquivo index.html em qualquer navegador moderno
3. Utilize o menu de navegação para alternar entre as funcionalidades
4. Preencha os formulários com as informações necessárias
5. Clique em "Enviar" para registrar os dados

Configuração do Google Sheets (Opcional)

Para conectar com sua própria planilha:

1. Crie uma planilha no Google Sheets
2. Acesse Extensões > Apps Script
3. Cole o script de backend e publique como Web App
4. Substitua a variável SCRIPT_URL no arquivo HTML pela URL do seu Web App

📱 Responsividade

O sistema foi desenvolvido com abordagem mobile-first, garantindo:

· Layout adaptável para smartphones
· Navegação otimizada para toque
· Botões grandes e de fácil acesso
· Scroll suave entre seções
· Experiência consistente em tablets e desktops

🎨 Design e UX

· Paleta de cores: Azul institucional (#0f3b5f) e tons complementares
· Tipografia: Inter, garantindo legibilidade
· Feedback visual: Animações suaves e toasts de confirmação
· Cards: Design limpo e organizado
· Botões: Efeitos hover e active para melhor interação

🔒 Segurança

· Validação de campos obrigatórios
· Feedback de erro para o usuário
· Confirmação visual após envio
· Desativação temporária do botão durante envio (evita duplicidade)

📦 Estrutura de Arquivos

```
sistema-gestao-cdd/
│
├── index.html              # Arquivo principal da aplicação
├── README.md              # Documentação do projeto
│
└── assets/ (opcional)
    └── (imagens e outros recursos)
```

🌐 Compatibilidade

Testado e compatível com:

· Google Chrome (últimas versões)
· Mozilla Firefox (últimas versões)
· Safari (últimas versões)
· Microsoft Edge (últimas versões)
· Navegadores mobile (iOS e Android)

📈 Próximas Melhorias (Roadmap)

· Implementar autenticação de usuários
· Adicionar relatórios e dashboards
· Incluir gráficos de produtividade
· Permitir exportação de dados
· Adicionar modo offline com sincronização
· Implementar notificações push
· Criar versão como PWA
· Adicionar histórico de registros

🤝 Contribuição

Sugestões e melhorias são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (git checkout -b feature/NovaFuncionalidade)
3. Commit suas mudanças (git commit -m 'Adiciona nova funcionalidade')
4. Push para a branch (git push origin feature/NovaFuncionalidade)
5. Abra um Pull Request

📄 Licença

Este projeto é de uso interno do CDD Itu. Para mais informações sobre uso e distribuição, entre em contato com a administração.

📞 Suporte e Contato

CDD Itu - Centro de Distribuição

· Responsável: Equipe de Gestão
· Sistema desenvolvido para otimização das operações diárias
· Para suporte técnico, reportar bugs ou sugerir melhorias, entre em contato com a gestão do CDD

🏆 Agradecimentos

A todos os colaboradores que utilizam o sistema diariamente e contribuem com feedbacks para sua melhoria contínua.

---

Versão: 1.0.0
Última atualização: Maio/2026
Status: ✅ Em produção

---

Este sistema foi desenvolvido para facilitar a gestão operacional do CDD Itu, promovendo eficiência e organização no dia a dia da equipe.
