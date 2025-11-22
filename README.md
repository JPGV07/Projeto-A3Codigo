Projeto A3 — Conversão, Hash e Simulação FCFS

Este projeto é um sistema web desenvolvido para a disciplina A3, contendo três funcionalidades principais:

Conversão de bases numéricas

Geração de Hash SHA-256

Simulação de escalonamento FCFS (First Come, First Served)

O projeto foi desenvolvido utilizando HTML, CSS e JavaScript puro.

Estrutura do Projeto /ProjetoA3 │── A3.html → Tela inicial com os nomes dos alunos │── A3pt2.html → Menu principal com as três funções │── A3C.html → Conversão de bases numéricas │── A3H.html → Geração de Hash SHA-256 │── A3S.html → Simulação FCFS │── README.md → Documentação do projeto

Alunos

João Pedro Gama Viegas, 
Kevin Suell Ferreira de Souza, 
Francisco Bezerra Neto, 
Felipe Willamis Meireles Fernandes, 

Instituição: Faculdade Internacional da Paraíba (FPB)

RELATÓRIO / DOCUMENTAÇÃO — Projeto A3
1. Problema que o sistema simula ou resolve

O projeto A3 é um sistema interativo desenvolvido em HTML, CSS e JavaScript, que tem como objetivo simular e demonstrar conceitos essenciais de Sistemas Computacionais e Segurança. Ele contém três ferramentas principais:

a) Conversão entre bases numéricas – Arquivo: A3C.html

Resolve o problema de conversão entre diferentes sistemas de numeração (binário, decimal, octal e hexadecimal).
O sistema permite que o usuário selecione a base de origem e visualize automaticamente o valor convertido nas outras bases.
Esse recurso reforça o entendimento sobre:
Representação interna dos dados no computador
Manipulação numérica em diferentes bases
Uso prático dessas bases em sistemas digitais e programação

b) Gerador de Hash SHA-256 – Arquivo: A3H.html

Resolve o problema de transformar um texto comum em um hash criptográfico SHA-256.
Esse tipo de algoritmo é utilizado em:
Verificação de integridade
Armazenamento seguro de senhas
Autenticação
Blockchain
A simulação demonstra:
Irreversibilidade do hash
Reprodutibilidade
Efeito avalanche (pequenas mudanças geram grandes diferenças no hash)

c) Simulação do algoritmo FCFS – Arquivo: A3S.html

Resolve o problema de visualizar o funcionamento do escalonamento de processos FCFS (First Come, First Served).
O sistema permite adicionar processos com seus tempos e gera:
Gráfico de Gantt
Tempo de espera
Tempo de retorno
Com isso, o usuário entende como o sistema operacional organiza processos na fila de execução.

d) Tela inicial e navegação – Arquivos: A3.html e A3pt2.html
São as páginas responsáveis pela navegação do projeto, oferecendo acesso organizado às três ferramentas.

2. Conceitos de Sistemas Computacionais e Segurança aplicados
Representação de Dados

Implementada na conversão de bases numéricas (A3C.html).
O sistema usa:
Base 2 (binário)
Base 8 (octal)
Base 10 (decimal)
Base 16 (hexadecimal)
Essas bases representam como dados são armazenados e processados internamente.
Criptografia e Segurança da Informação
Aplicada no gerador de hash (A3H.html), utilizando o algoritmo SHA-256 através da API nativa do navegador (crypto.subtle.digest()).
Conceitos envolvidos:
Integridade
Funções criptográficas unidirecionais
Armazenamento seguro de dados
Não-reversão
Gerenciamento de Processos
Implementado na simulação FCFS (A3S.html).
Conceitos aplicados:
Escalonamento não preemptivo
Ordem de chegada
Cálculo de waiting time e turnaround time
Representação com gráfico de Gantt
Esses conceitos fazem parte do funcionamento interno de sistemas operacionais.

3. Usabilidade e acessibilidade do sistema

Interface Simples e Intuitiva
Botões bem posicionados
Cores suaves e layout limpo
Foco em uma função por página
Feedback Imediato
Conversões aparecem automaticamente
Erros são avisados de forma clara
Processos atualizam de forma dinâmica
Acessibilidade
Textos com bom tamanho
Layout responsivo
Campos com boa área de clique
Organização do Código
HTML semântico
CSS limpo
JavaScript direto e fácil de entender

4. Conclusão:
O projeto A3 reúne três ferramentas educacionais que simulam conceitos essenciais de Sistemas Computacionais, Sistemas Operacionais e Segurança da Informação.
O sistema permite que o usuário aprenda os conceitos de forma prática através de interação, visualização e experimentação.
