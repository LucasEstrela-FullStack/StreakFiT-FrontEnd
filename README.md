# StreakFit Frontend 🎨💪

Frontend do **StreakFit**, uma aplicação moderna de gestão de treinos com suporte a Personal Trainer via IA. Construído com as tecnologias web mais recentes de 2026.

## ✨ Tecnologias

- **Framework**: [Next.js 16 (App Router)](https://nextjs.org/)
- **Linguagem**: TypeScript
- **Estilização**: **Tailwind CSS 4** + Radix UI
- **Integração AI**: [Vercel AI SDK (@ai-sdk/react)](https://sdk.vercel.ai/)
- **Gerenciamento de Estado**: [nuqs](https://nuqs.47ng.com/) (para filtros e estado persistido na URL)
- **Formulários**: React Hook Form + Zod
- **Ícones**: Lucide React
- **Animações**: tw-animate-css

## 🚀 Funcionalidades Principais

- **Dashboard de Treinos**: Visualização completa de planos ativos e histórico.
- **Onboarding Inteligente**: Passo a passo para cadastrar peso, altura e objetivos (pode ser feito via chat AI).
- **Personal Trainer AI**: Chat interativo integrado para tirar dúvidas, receber dicas e criar planos automaticamente.
- **Estatísticas Avançadas**: Gráficos e dashboards de evolução.
- **Auth Integrado**: Fluxos de login e registro via Better-Auth.

## ⚙️ Instalação e Execução

1.  **Instale as dependências**:
    ```bash
    npm install
    ```

2.  **Configuração de Ambiente**:
    Crie o arquivo `.env` e configure os endereços da API conforme o arquivo `.env.example`:
    ```bash
    cp .env.example .env
    ```

3.  **Inicie o servidor de desenvolvimento**:
    ```bash
    npm run dev
    ```

4.  **Acesse no navegador**:
    `http://localhost:3000`

## 📂 Estrutura de Diretórios

```text
app/                 # Páginas (App Router)
  ├── auth/          # Login e Cadastro
  ├── onboarding/    # Configuração inicial do usuário
  ├── profile/       # Gestão de conta
  ├── stats/         # Dashboard de métricas
  ├── workout-plans/ # Dashboard de treinos
components/          # Componentes de UI (Radix + Shadcn-like)
lib/                 # Hooks, utilitários e constantes
public/              # Assets estáticos
```

## 🛠️ Build e Produção

Para gerar o build de produção:
```bash
npm run build
```
Para rodar a versão de produção:
```bash
npm run start
```