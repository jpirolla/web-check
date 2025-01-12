
# Monitoramento de Sites
Este é um projeto simples em Go para monitorar sites, verificar se estão online e registrar as informações em logs. O programa lê um arquivo de texto contendo os URLs dos sites e os testa periodicamente para verificar se estão funcionando corretamente. O usuário pode iniciar o monitoramento, exibir os logs ou sair do programa.

# Funcionalidades
- Monitoramento de sites: O programa monitora uma lista de sites e verifica se estão acessíveis (status 200) a cada 5 segundos.
- Exibição de Logs: O usuário pode consultar os logs de monitoramento, mostrando se o site estava online ou não em determinado momento.
- Registro de Logs: Cada status de site é registrado em um arquivo de log com a data e hora do teste.
- Saudação personalizada: O programa solicita o nome do usuário e exibe uma saudação personalizada.

## Como Usar
### Pré-requisitos
1. Go instalado em sua máquina. Você pode baixar o Go em https://golang.org/dl/.
2. Um arquivo sites.txt contendo uma lista de URLs de sites a serem monitorados. Cada URL deve estar em uma linha separada.

#### Passos
- Clone ou baixe o repositório do projeto para sua máquina.
- Certifique-se de que o arquivo sites.txt esteja presente na mesma pasta do programa, contendo os URLs dos sites a serem monitorados.
- Execute o programa com o comando:

```bash
go run main.go
```

O programa irá exibir um menu com as seguintes opções:
```bash
1: Iniciar o monitoramento dos sites.
2: Exibir os logs de monitoramento.
0: Sair do programa.
```