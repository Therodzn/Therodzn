

# Sobre Mim | About Me
> A tecnologia sempre foi mais do que apenas ferramenta para mim — é uma forma de pensar, criar e transformar. Desde cedo, percebi que tinha curiosidade por entender como as coisas funcionavam, e isso me levou naturalmente ao mundo da programação e do desenvolvimento de sistemas. O que começou como um interesse se tornou um caminho de aprendizado contínuo, marcado por projetos desafiadores e descobertas diárias.

> Ao longo da minha trajetória, tive o prazer de trabalhar com desenvolvimento de jogos e gerenciamento de servidores, áreas que exigem não só habilidade técnica, mas também criatividade e pensamento estratégico. Cada linha de código escrita e cada problema resolvido me aproximou um pouco mais da visão que tenho: usar a tecnologia como força motriz para soluções inteligentes e inovadoras.

> Hoje, estou em constante busca por evolução. Não basta apenas saber programar — quero entender o impacto real da tecnologia no mundo e usá-la para construir algo que vá além do código: algo que inspire, conecte e transforme.

# Ferramentas 
![img icons8](https://github.com/user-attachments/assets/6c77fc52-9d3b-49d5-acd7-5642ec17686b)
![1736445932939](https://github.com/user-attachments/assets/f120943c-785c-41d3-9640-b75affe9b37e)



# 🤖 Fallet Discord Bot

Bot Discord profissional para o servidor Fallet.

## 📋 Pré-requisitos

- Node.js (versão 16 ou superior)
- npm ou yarn
- Token do bot Discord

## 🚀 Instalação

1. Clone ou baixe este projeto
2. Instale as dependências:
   ```bash
   npm install
   ```

3. Configure o arquivo `.env` com seu token do Discord

4. Execute o bot:
   
   **Opção 1 - Usando arquivos .bat (Windows):**
   ```bash
   # Duplo clique no arquivo ou execute:
   start_bot.bat
   ```
   
   **Opção 2 - Usando npm:**
   ```bash
   npm start
   ```

   Para desenvolvimento (com auto-reload):
   ```bash
   npm run dev
   ```

## 🛑 Parar o Bot

**Usando arquivo .bat:**
```bash
stop_bot.bat
```

**Ou pressione `Ctrl+C` no terminal onde o bot está rodando.**

## ⚙️ Configuração

### Token do Discord
O token já está configurado no arquivo `.env`. Certifique-se de que o bot tenha as permissões necessárias no servidor Discord.

### Permissões Necessárias
- Ler Mensagens
- Enviar Mensagens
- Gerenciar Mensagens
- Usar Comandos de Barra
- Ver Canais

## 🎯 Comandos Básicos

- `!ping` - Testa se o bot está funcionando
- `!fallet` - Mensagem de boas-vindas

## 📁 Estrutura do Projeto

```
BOT-FALLET/
├── index.js          # Arquivo principal do bot
├── package.json      # Dependências e scripts
├── .env             # Variáveis de ambiente (token)
├── .gitignore       # Arquivos ignorados pelo git
├── start_bot.bat    # Script para iniciar o bot (Windows)
├── stop_bot.bat     # Script para parar o bot (Windows)
└── README.md        # Este arquivo
```

## 🔧 Próximos Passos

Este é apenas o setup básico. Funcionalidades adicionais serão implementadas conforme necessário:

- Sistema de moderação
- Comandos administrativos
- Integração com banco de dados
- Sistema de logs
- Comandos personalizados

## 📞 Suporte

Para adicionar novas funcionalidades ou reportar problemas, entre em contato com a equipe de desenvolvimento.

---

**Status:** ✅ Bot básico configurado e pronto para uso
