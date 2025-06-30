# Infra-servweb
Script Bash para provisionamento automático de um servidor Apache



Script de Infraestrutura como Código (IaC) para automatizar a implantação de um servidor web Apache em ambiente Linux.

## 📋 Descrição

Este projeto contém scripts Bash para provisionamento automático de:
- Servidor Apache HTTPD
- Configurações básicas de firewall
- Deploy de aplicação web de exemplo
- Configurações essenciais de segurança

## 🚀 Como Usar

### Pré-requisitos
- Sistema operacional Linux (Ubuntu/Debian recomendado)
- Acesso root/sudo
- Conexão com internet

### Execução básica
```bash
sudo bash provisionamento_web.sh

Opções avançadas

    Customizar aplicação:
    bash

export APP_URL="sua-url-aqui.zip"
sudo -E bash provisionamento_web.sh

Modo verbose (para depuração):
bash

    sudo bash provisionamento_web.sh --verbose

🛠️ Funcionalidades

    Instalação automática do Apache2

    Configuração de firewall (UFW)

    Deploy de aplicação web

    Configuração de permissões

    Verificação de status do serviço

🌐 Acesso

Após a execução, o servidor estará disponível em:
text

http://<seu-ip>

📌 Melhores Práticas

    Revise as variáveis no início do script

    Para ambientes de produção:

        Configure HTTPS (Certbot)

        Implemente monitoramento

        Adicione regras de firewall adicionais

📄 Licença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para detalhes.



### Dicas para o arquivo README.md:
1. Adicione badges no topo (ex: ![GitHub license](https://img.shields.io/github/license/seu-usuario/seu-repo))
2. Inclua uma seção de "Contribuição" se for um projeto aberto
3. Adicione um diagrama de arquitetura simples usando ```mermaid
4. Para projetos complexos, inclua uma matriz de compatibilidade com versões
