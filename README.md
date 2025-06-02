# Manipulação de dados com Pandas

Este projeto automatiza o processamento de dados de carros utilizando Python e a biblioteca Pandas.

## O que o código faz

1. **Importa dados de duas planilhas Excel**  
   - `tabela_carros_ano.xlsx`: contém informações sobre carros, valores e anos.
   - `tabela_marca_carros.xlsx`: contém informações sobre marcas dos carros.

2. **Limpeza e padronização dos dados**  
   - Renomeia colunas para facilitar o uso.
   - Remove espaços e padroniza os nomes dos carros para minúsculas.

3. **Mescla os dados das duas planilhas**  
   - Junta as informações dos carros com suas respectivas marcas.

4. **Renomeia colunas para melhor compreensão**  
   - Ajusta os nomes das colunas após a mesclagem.

5. **Remove linhas com dados ausentes**  
   - Elimina registros incompletos para garantir a qualidade dos dados.

6. **Calcula desconto no valor dos carros**  
   - Adiciona uma coluna com 10% de desconto para carros acima de R$ 50.000.

7. **Exporta o resultado para uma nova planilha Excel**  
   - Salva o dataframe final em `tabela_carros_ano_atualizada.xlsx`.
