# Painel_WireGuard_Flask
Este projeto é um painel web desenvolvido com Flask para gerenciar clientes do WireGuard de forma simples, leve e eficiente, sem uso de banco de dados — apenas arquivos JSON. Ele permite cadastrar, visualizar, remover e gerar configurações prontas para MikroTik, além de exibir o status da VPN.

✅ Funcionalidades
Login com autenticação simples (usuários em users.json)
Adição de novos clientes com:
Nome
Chave pública
IP interno
Remoção de clientes
Exibição de todos os clientes cadastrados
Geração automática de configuração para MikroTik:
Interface cliente
Endereço IP
Chaves públicas/privadas
Endpoint e porta
Exibição de status da interface WireGuard
Execução de script bash para obter conexões ativas e tráfego
🧰 Tecnologias Utilizadas
Python 3
Flask
HTML + Jinja2
CSS básico
Bash (para script wg_helper.sh)
JSON (armazenamento local de dados)
