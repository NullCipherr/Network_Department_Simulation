### Projeto de Redes no Cisco Packet Tracer

Este repositório contém os arquivos e documentação do Trabalho Prático para a matéria de Redes de Computadores, desenvolvido utilizando a ferramenta **Cisco Packet Tracer**. O objetivo principal do projeto é configurar e simular a rede de um Departamento de Computação, que inclui laboratórios, secretaria, sala de professores e Data Center, com foco em práticas de roteamento estático e dinâmico, além de configuração de serviços essenciais como HTTP, FTP, e DNS.

#### Estrutura do Projeto

O projeto está dividido em duas principais partes, conforme especificado abaixo:

#### Parte 1: Configuração da Rede do Departamento de Computação

- **Topologia da Rede**: Configuração de uma rede que inclui:
  - Dois laboratórios de ensino com 10 máquinas cada.
  - Secretaria com 5 computadores e uma impressora.
  - Sala de professores com 8 máquinas e uma impressora.
  - Data Center contendo servidores DHCP, HTTP e DNS.
  
- **Roteadores**: Implementação de pelo menos três roteadores interligados com roteamento estático ou dinâmico (RIP).
  
- **Sub-redes**:
  - Configuração otimizada de endereços IP privados.
  - Configuração de redes entre roteadores com máscara /30.
  
- **Serviços**:
  - Configuração de HTTP e FTP em um servidor.
  - Configuração de DNS em outro servidor, incluindo registros A, NS e CNAME.
  
- **Testes e Simulações**:
  - Envio de ping entre computadores e servidores.
  - Acesso ao servidor HTTP via navegador.
  - Simulação e análise do comportamento da rede com o servidor DNS ativado e desativado.

#### Arquivos Incluídos

- **.pkt**: Arquivo de configuração da rede no Cisco Packet Tracer.
- **Screenshots**: Imagens detalhadas de cada etapa de configuração e resultados dos testes.
- **Relatório.pdf**: Documento contendo a descrição do processo, explicações passo a passo das simulações realizadas, e as conclusões obtidas.

### Como Utilizar

1. **Instale o Cisco Packet Tracer**: [Link para Download](https://www.netacad.com/pt-br/courses/packet-tracer)
2. **Abra o arquivo `.pkt`**: Utilize o Cisco Packet Tracer para carregar a topologia da rede e explorar as configurações.
3. **Explore as Simulações**: Siga os passos descritos no relatório para replicar os testes e entender o funcionamento da rede.

### Requisitos

- Cisco Packet Tracer (versão 7.3 ou superior).
- Conhecimento básico em redes de computadores, roteamento e configuração de serviços de rede.

Este projeto é uma excelente oportunidade para praticar e aplicar conceitos fundamentais de redes de computadores em um ambiente simulado, proporcionando uma visão prática e detalhada do funcionamento de uma rede departamental complexa.
