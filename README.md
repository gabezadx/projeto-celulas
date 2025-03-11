# projeto-celulas
um programa para gerir as celulas 

Desenvolver um programa simples em HTml CSS js e PYTHON. O programa irá permitir que o usuário insira informações sobre uma reunião, como o número de pessoas presentes, a data da reunião e o valor adquirido, e, em seguida, gere um relatório com esses dados que serão enviados ao usuario admin

Requisitos Funcionais
Entrada de Dados:

O programa deve permitir que o usuário insira as seguintes informações:
Quantidade de pessoas: Um número inteiro representando a quantidade de pessoas presentes na reunião.
Data da reunião: Uma string representando a data da reunião, no formato DD/MM/AAAA.
Valor adquirido: Um número decimal (float) representando o valor de dinheiro adquirido na reunião.
Validação de Dados:

O programa deve validar as entradas fornecidas pelo usuário:
Quantidade de pessoas: O número deve ser positivo. Se for menor ou igual a zero, o programa deve exibir um erro.
Data da reunião: O formato da data deve ser DD/MM/AAAA. Se o formato estiver incorreto, o programa deve exibir um erro.

Valor adquirido: 
Deve ser um número válido (positivo e com casas decimais, se necessário).
O programa deve exibir um erro se o valor não for numérico.

Geração do Relatório:
O programa deve gerar um relatório simples contendo as seguintes informações:
Data da reunião
Quantidade de pessoas presentes
Valor adquirido na reunião
O relatório gerado deve ser exibido em um label na interface gráfica.

Exibição de Erros:
O programa deve mostrar mensagens de erro claras e úteis se:
A quantidade de pessoas for inválida (não um número positivo).
A data estiver no formato errado ou não for válida.
O valor adquirido não for um número válido.

Requisitos Não Funcionais

Usabilidade:

A interface gráfica deve ser simples e intuitiva.
Os campos de entrada e botões devem ser claramente identificados com rótulos explicativos.
O botão de "Gerar Relatório" deve ser facilmente acessível.
O layout deve ser organizado de forma clara, com espaçamento adequado entre os componentes da interface.

Armazenamento Temporário:
O programa não necessita armazenar dados permanentemente em arquivos, mas pode exibir e salvar o relatório temporariamente na interface.

Feedback ao Usuário:
O usuário deve ser notificado sobre qualquer erro ou sucesso com mensagens claras.
Caso os dados sejam válidos, o programa exibe o relatório diretamente na interface.
