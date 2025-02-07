# Fluxograma para Processos de Dar Andamento no Super Sapiens

Este projeto apresenta um fluxograma para o andamento de processos no sistema **Super Sapiens**. O objetivo é ilustrar a sequência de etapas desde o recebimento do processo até o seu encerramento. O fluxograma abrange a análise do tipo de processo, sua redistribuição e ações relacionadas.

## Estrutura do Fluxograma

O fluxograma é composto pelas seguintes etapas:

1. **Início**: O processo começa com o recebimento de um novo processo.
2. **Recebimento de Processo na Caixa**: O processo é recebido na caixa de entrada.
3. **Redistribuição ao Protocolo**: O processo é redistribuído automaticamente ao protocolo.
4. **Análise do Tipo de Processo**: O processo é analisado para identificar seu tipo e a ação necessária.
5. **Casos**: Dependendo da análise, o processo segue para um dos três casos:
   - **Cobrança/Parcelamento → Enviar para Rayanne**
   - **Inscrição em Dívida Ativa → Dar Entrada**
   - **Contencioso → Redistribuir no Sapiens para o Último Procurador que Trabalhou**
6. **Encaminhamento ao Responsável**: O processo é enviado para o responsável, que irá orientá-lo e encaminhá-lo ao protocolo com as observações necessárias.
7. **Encerramento do Processo**: As secretárias movimentam o processo para encerramento com orientação do procurador.
8. **Fim**: O processo é finalizado.

## Como o Fluxograma Funciona

- O processo começa no ponto de **Recebimento** e passa por diversas etapas conforme definido no fluxograma.
- Em cada etapa, o processo pode ser direcionado para diferentes ações de acordo com a análise feita.
- O fluxograma visualiza as decisões e os encaminhamentos feitos durante o processo, garantindo que todas as etapas sejam cumpridas corretamente.

## Tecnologias Utilizadas

- **Python**: A linguagem de programação usada para gerar o fluxograma.
- **Graphviz**: A biblioteca utilizada para criar o gráfico do fluxograma.

## Como Executar

Para executar o script e gerar o fluxograma:

1. Instale as dependências:
   pip install graphviz

Execute o script Python:
python fluxograma_sapiens.py

O fluxograma será gerado como uma imagem PNG na pasta de saída configurada no script.

Contribuições
Sinta-se à vontade para contribuir com melhorias, correções ou novas funcionalidades. Caso queira adicionar algo ao fluxograma, por favor, faça um fork deste repositório, crie uma branch e submeta um pull request.
