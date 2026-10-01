# Construtora Unno | TypeScript Enterprise Migration

Evolução do projeto "Construtora Unno" para um padrão de desenvolvimento corporativo rigoroso, migrando toda a base de código JavaScript para **TypeScript**. 

## Visão Geral do Projeto
Esta iteração eleva a segurança e previsibilidade do código. A implementação de tipagem estática assegura que os contratos de dados são respeitados entre componentes, eliminando *bugs* de execução (runtime errors) comuns em aplicações JavaScript de larga escala.

## Tecnologias Utilizadas
* **React 18 + Vite:** Ambiente de desenvolvimento ultra-rápido configurado para módulo `bundler`.
* **TypeScript:** Tipagem estática rigorosa (`Strict Mode` ativado).
* **SASS (SCSS):** Arquitetura de estilos modular.

## Destaques da Migração TypeScript
* **Interfaces de Dados:** Definição rigorosa de modelos de dados, como a interface `Project`, garantindo a integridade dos metadados exibidos na galeria de portfólio.
* **Tipagem de Formulários e Eventos:** O componente de contacto implementa a interface `ContactFormData` e tipagem estrita de eventos do DOM (`React.ChangeEvent`, `React.FormEvent`), blindando a recolha de dados de inputs, selects e textareas.
* **Proteção de Null Checks:** Resolução de inferências e asserções não-nulas (`!`) na inicialização da árvore do React.
* **Configuração de Ambiente:** Configuração avançada do `tsconfig.json` e declaração de tipos de assets (`vite-env.d.ts`) para suporte nativo a importações de media.

## Como Executar Localmente
1. Clone o repositório: `git clone https://github.com/SEU-USUARIO/unno-engenharia-react-ts.git`
2. Instale as dependências: `npm install`
3. Inicie o servidor de desenvolvimento: `npm run dev`