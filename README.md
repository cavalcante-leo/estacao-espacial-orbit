# 🚀 Missão Suporte Vital - Operação Estação Espacial

Sistema de monitoramento e verificação dos parâmetros críticos de suporte à vida a bordo do módulo orbital. Este projeto foi desenvolvido para garantir a segurança e a operacionalidade dos sistemas essenciais durante a missão.

## 🌍 Camadas de Ambiente (Deploy)

O projeto segue o fluxo de versionamento e entrega contínua baseado em três ambientes principais:

- **`develop`** (Desenvolvimento)
  - Ambiente local e de integração contínua.
  - Utilizado para validação de novas funcionalidades, correções de bugs e testes unitários.
  - Código em constante evolução, podendo conter instabilidades temporárias.

- **`stage`** (Homologação / Validação)
  - Ambiente de pré-produção que replica fielmente o ambiente real.
  - Realiza a simulação completa das condições da estação espacial.
  - Onde são executados os testes de carga, segurança e aceitação antes de qualquer implantação no ambiente final.

- **`main`** (Produção)
  - Ambiente estável e oficial.
  - Contém a versão aprovada e validada do sistema, atualmente em execução no módulo espacial.
  - Qualquer atualização nesta branch passa rigorosamente pelos ambientes `develop` e `stage` antes do merge.

## 👨‍🚀 Tripulação (Desenvolvedores)

O projeto é mantido pelos seguintes engenheiros de software responsáveis pela manutenção do código fonte do sistema de suporte vital:

- **cavalcante-leo** (Engenheiro de Software / Comandante de Código)