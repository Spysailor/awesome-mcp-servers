# Frameworks pour le développement de serveurs MCP

Cette liste présente les frameworks disponibles pour faciliter le développement de serveurs MCP (Model Context Protocol) dans différents langages de programmation.

## Frameworks Python

- [FastMCP](https://github.com/jlowin/fastmcp) 🐍 - Un framework de haut niveau pour créer des serveurs MCP en Python.
- [rectalogic/langchain-mcp](https://github.com/rectalogic/langchain-mcp) 🐍 - Support d'appels d'outils MCP dans LangChain.

## Frameworks TypeScript/JavaScript

- [FastMCP](https://github.com/punkpeye/fastmcp) 📇 - Un framework de haut niveau pour construire des serveurs MCP en TypeScript.
- [gabfr/waha-api-mcp-server](https://github.com/gabfr/waha-api-mcp-server) 📇 - Serveur MCP avec spécifications openAPI.
- [Genkit MCP](https://github.com/firebase/genkit/tree/main/js/plugins/mcp) 📇 – Intégration entre Genkit et le MCP.
- [LiteMCP](https://github.com/wong2/litemcp) 📇 - Framework léger pour serveurs MCP en JavaScript/TypeScript.
- [marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) - Extension CodeMirror qui implémente le MCP.
- [mcp-framework](https://github.com/QuantGeekDev/mcp-framework) 📇 - Framework TypeScript élégant pour MCP.
- [mcp-proxy](https://github.com/punkpeye/mcp-proxy) - 📇 Proxy SSE TypeScript pour les serveurs MCP.
- [ribeirogab/simple-mcp](https://github.com/ribeirogab/simple-mcp) 📇 - Bibliothèque TypeScript simple pour MCP.

## Frameworks Go

- [Foxy Contexts](https://github.com/strowk/foxy-contexts) 🏎️ - Bibliothèque Golang pour écrire des serveurs MCP de manière déclarative.
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) 🏎️ - SDK Golang pour construire des serveurs et clients MCP.
- [metoro-io/mcp-golang](https://github.com/metoro-io/mcp-golang) 🏎️ - Framework Golang axé sur la sécurité des types.

## Frameworks Rust

- [mcp-rs-template](https://github.com/linux-china/mcp-rs-template) 🦀 - Modèle de serveur CLI MCP pour Rust.
- [poem-web/poem-mcpserver](https://github.com/poem-web/poem/tree/master/poem-mcpserver) 🦀 - Implémentation du serveur MCP pour Poem.

## Frameworks Java/.NET

- [mullerhai/sakura-mcp](https://github.com/mullerhai/sakura-mcp) 🦀 ☕ - Framework MCP Scala.
- [quarkiverse/quarkus-mcp-server](https://github.com/quarkiverse/quarkus-mcp-server) ☕ - SDK Java pour construire des serveurs MCP avec Quarkus.
- [salty-flower/ModelContextProtocol.NET](https://github.com/salty-flower/ModelContextProtocol.NET) #️⃣ 🏠 - SDK C# pour .NET 9 avec compatibilité NativeAOT.
- [spring-ai-mcp](https://github.com/spring-projects-experimental/spring-ai-mcp) ☕ 🌱 - SDK Java et intégration Spring Framework.

## Outils Multilangage

- [http4k MCP SDK](https://mcp.http4k.org) 🐍 - SDK Kotlin fonctionnel basé sur le toolkit Web http4k.
- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) 🤖 🔌 - Construction d'agents efficaces avec serveurs MCP.
- [Template MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/template) 📇 - Modèle simple pour construire un nouveau serveur MCP.

## Caractéristiques des frameworks

### Performances et Optimisation
- Frameworks Go et Rust offrent généralement les meilleures performances
- FastMCP (Python) a été conçu pour optimiser la manipulation de données volumineuses

### Facilité d'utilisation
- FastMCP (TypeScript) et LiteMCP sont les plus simples pour débuter
- Template MCP Server fournit une base minimale pour commencer rapidement

### Intégration avec écosystèmes existants
- langchain-mcp permet d'intégrer des outils MCP dans les chaînes LangChain
- spring-ai-mcp s'intègre bien dans l'écosystème Spring
- quarkus-mcp-server utilise les capacités de Quarkus pour la compilation native

### Support des transports
- La plupart des frameworks supportent SSE (Server-Sent Events)
- mcp-proxy est spécialisé dans la conversion entre différents modes de transport

## Comment choisir un framework

1. **Langage préféré** : Choisissez le framework correspondant à votre langage de programmation préféré
2. **Performance vs Facilité** : Les frameworks Go/Rust sont plus performants, JS/TS/Python plus accessibles
3. **Type de serveur** : Pour des serveurs complexes, privilégiez les frameworks avec abstractions de haut niveau
4. **Intégration** : Choisissez un framework qui s'intègre bien avec votre pile technologique existante
5. **Maturité** : Vérifiez l'activité du projet, le nombre d'étoiles GitHub, et la qualité de la documentation
