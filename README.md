Neste exemplo utilizei a ferramenta Ansible para colocar uma máquina da familia debian direto ao monitoramento do Zabbix Server. Foda!

Alguns pontos:
1. No arquivo do zabbix*.conf é necessário já estar configurado (inclusive com informações do server), e com o nome de zabbix em hostname, pois será substituído atráves do sed command.
2. Adequar também o arquivo zabbix_server_vars com as credenciais e endereços de seu servidor, para que a API entre em vigor.