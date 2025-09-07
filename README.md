# 📌 ClickDesk - Sistema de Chamados com IA (PIM IV - UNIP)

Projeto acadêmico desenvolvido no âmbito do **PIM IV (Análise e Desenvolvimento de Sistemas - UNIP)**, com continuidade do PIM III.  
O sistema **ClickDesk** tem como objetivo **automatizar a gestão de chamados técnicos** em empresas de pequeno e médio porte, utilizando **Inteligência Artificial simulada** para classificação, priorização e sugestões de solução.

---

## 🎯 Objetivos do Projeto

- Estruturar um sistema integrado de **Suporte Técnico**.
- Aplicar **IA simulada** para análise de chamados e sugestão de respostas.
- Desenvolver aplicações para **Desktop, Web e Mobile**.
- Garantir **segurança e aderência à LGPD** no tratamento de dados.
- Fornecer **relatórios gerenciais** e indicadores de desempenho.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagens**: C#, ASP.NET, Java/Kotlin ou .NET MAUI  
- **Banco de Dados**: MS SQL Server  
- **Frontend Web**: ASP.NET MVC / Blazor  
- **Mobile**: Android Studio (Java/Kotlin) ou .NET MAUI  
- **Metodologia**: Scrum + Kanban  
- **Versionamento**: GitHub  

---

## 📂 Estrutura do Repositório

```
ClickDesk-PIM-IV/
│
├── docs/                       → Documentos acadêmicos (originais e convertidos)
├── sprints/                    → Desenvolvimento organizado por semanas
├── src/                        → Código-fonte consolidado
├── tests/                      → Testes automatizados
├── assets/                     → Recursos visuais (mockups, slides, logos)
└── .github/                    → Configurações do GitHub (CI/CD, issues)
```

---

## 📅 Organização em Sprints (Checklist PIM IV)

- **Sprint 01 – Organização**: Regras de negócio, GitHub, ferramentas.  
- **Sprint 02 – Banco de Dados**: DER, criação de tabelas e inserts iniciais.  
- **Sprint 03 – Conexão inicial**: Script SQL + login conectado ao banco.  
- **Sprint 04 – CRUD Usuário (Desktop)**: Cadastro e login de usuários.  
- **Sprint 05 – CRUD Chamados (Desktop)**: Cadastro e listagem de chamados.  
- **Sprint 06 – Web: Estrutura**: Projeto ASP.NET, tela de login e abertura de chamado (front).  
- **Sprint 07 – Web: CRUD**: Conexão com banco, abertura e listagem de chamados.  
- **Sprint 08 – Mobile: Estrutura**: Projeto Android/.NET MAUI, tela de login e abertura de chamado.  
- **Sprint 09 – Mobile: Conexão**: Integração com banco/API, abertura e listagem de chamados.  
- **Sprint 10 – IA Simulada**: Base de conhecimento (FAQ) no banco e telas de consulta.  
- **Sprint 11 – Relatórios e Refinamento**: Relatórios por status, filtros e usabilidade.  
- **Sprint 12 – Testes e Apresentação**: Fluxo completo, testes finais, slides e demo.  

---

## ▶️ Como Executar

1. **Clone o repositório**
   ```bash
   git clone https://github.com/SEU-USUARIO/ClickDesk-PIM-IV.git
   cd ClickDesk-PIM-IV
   ```

2. **Banco de Dados**
   - Crie o banco no SQL Server.
   - Execute o script inicial em `sprints/sprint02_banco_dados/script_inicial.sql`.

3. **Aplicação Desktop**
   - Abra `src/desktop/ClickDesk.Desktop.sln` no Visual Studio.
   - Compile e rode a aplicação.

4. **Aplicação Web**
   - Abra `src/web/ClickDesk.Web.sln`.
   - Configure a string de conexão no `appsettings.json`.
   - Rode via IIS Express ou `dotnet run`.

5. **Aplicação Mobile**
   - Abra `src/mobile/` no Android Studio ou Visual Studio.
   - Configure a conexão com a API/banco.
   - Compile e rode em emulador ou dispositivo real.

---

## 👨‍💻 Equipe

- Aluno 1 – RA XXXXXXX  
- Aluno 2 – RA XXXXXXX  
- Aluno 3 – RA XXXXXXX  
- Aluno 4 – RA XXXXXXX  

---

## 📚 Referências

- SOMMERVILLE, Ian. *Engenharia de Software*. 10ª ed. Pearson, 2019.  
- PRESSMAN, Roger S.; MAXIM, Bruce R. *Engenharia de Software: uma abordagem profissional*. 8ª ed. AMGH, 2016.  
- Documentação oficial da **Microsoft .NET** e **SQL Server**.  
