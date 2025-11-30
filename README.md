# Projeto Prático de Cibersegurança – Ataques de Força Bruta com Medusa

Este repositório documenta um projeto prático para o desafio da DIO, simulando testes de força bruta usando Kali Linux (atacante) e Metasploitable 2 / DVWA (vítimas). O objetivo é demonstrar compreensão das ferramentas, comandos e medidas de mitigação.

## Ambiente (simulado)
- Kali Linux (atacante)
- Metasploitable 2 (vítima) com DVWA
- Rede interna (Host-only / NAT)
- Ferramentas: medusa, hydra, nmap, enum4linux

## Arquivos entregues
- `wordlists/users.txt` — lista de usuários
- `wordlists/passwords.txt` — lista de senhas
- `images/` — pasta para evidências (placeholder)

## Comandos usados (exemplos reais)
- Varredura de serviços:
- Força bruta FTP com Medusa:
- Ataque a formulário web (DVWA) com Hydra:
- Password spraying SMB com Medusa:

## Resultados (simulados)
- FTP: `admin:toor` — acesso obtido.  
- DVWA: `admin:123456` — acesso obtido em configuração Low.  
- SMB: `guest:123456` — acesso obtido via password spraying.

## Mitigações recomendadas
- Políticas de senha forte e expiração
- Bloqueio temporário ou rate limiting após tentativas falhas
- MFA (autenticação multifator)
- WAF e monitoramento de logs / IDS
- Remover/alterar contas padrão e desabilitar serviços desnecessários

## Observações
Este repositório documenta a metodologia e os comandos necessários para reproduzir os testes em um laboratório controlado (Kali + Metasploitable). As evidências reais podem ser adicionadas na pasta `images/` caso o laboratório seja executado.

## Créditos
Projeto entregue como desafio prático da DIO.
