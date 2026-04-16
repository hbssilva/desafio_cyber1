# desafio_cyber1
Entrega Conteúdo Desafio Cyber

## Configurar o ambiente: duas VMs (Kali Linux e Metasploitable 2) no VirtualBox, com rede interna (host-only) (telas 01 a 04);

## Executar ataques simulados: força bruta em FTP, automação de tentativas em formulário web (DVWA) e password spraying em SMB com enumeração de usuários (telas 06 a 22);

## Documentar os testes: wordlists simples, comandos utilizados, validação de acessos e recomendações de mitigação:

- Comandos utilizados ao longo dos testes:
  - Ping (testar acesso a máquina alvo);
  - NMAP (verificar portas abertas na máquina alvo);
  - Echo (simular logins e senhas disponíveis para máquina alvo (HTTP, SMB));
  - Medusa (varredura de logins e senhas na máquina alvo válidas);
  - LESS (para enumerar usuários na máquina alvo);

## Recomendações de Mitigação:

- Autenticação multifator, exigindo múltiplas formas de acesso além do login e senha, a fim de restringir acessos não autorizados;
- Biometria e reconhecimento facial: Oferecem níveis superiores de segurança física e lógica, dificultando fraudes de identidade;
- Firewalls de nova geração (NGFW) e EDR: Filtram tráfego malicioso e monitoram endpoints para isolar dispositivos comprometidos automaticamente;
- Treinamento contínuo e simulações de phishing: Capacitam os funcionários a identificar ameaças de engenharia social, que são vetores comuns de ataques;
- Auditorias periódicas e gestão de identidades: Garantem que permissões e credenciais sejam atualizadas regularmente, desativando contas inativas e revisando acessos;
- Integração de sistemas: Conecta controle de acesso, videomonitoramento e alarmes para criar uma rede inteligente com resposta rápida a incidentes;

