Para reproduzir os dados:

1.  **Instale o `pnadium`:** `!pip install -q pnadium` (se ainda não estiver instalado)
2.  **Rode o Caminho A:** A célula `01084271` baixa os microdados da PNAD Contínua diretamente do FTP do IBGE e os salva como `dados/01_bruto.parquet`.
3.  **Use o Caminho B:** Após a primeira execução do Caminho A, você pode carregar os dados rapidamente a partir do arquivo `.parquet` usando a célula `45bfbd54` (Caminho B).

**O que está em `dados/01_bruto.parquet`:**

Este arquivo contém uma fração aleatória dos microdados da PNAD Contínua do 3º trimestre de 2022, com as seguintes variáveis (originalmente solicitadas na célula `01084271`):

*   **Identificação e Geografia:** `Ano`, `Trimestre`, `UF`, `V1022` (situação domicílio), `V1023` (tipo área)
*   **Pessoa:** `V2007` (sexo), `V2010` (raça/cor), `V2009` (idade), `VD2002` (condição domicílio), `V2001` (pessoas domicílio)
*   **Educação:** `VD3004` (escolaridade), `VD3005` (anos estudo), `V3002` (frequenta escola)
*   **Trabalho:** `VD4002` (ocupação), `VD4009` (posição ocupação), `VD4010` (setor atividade), `VD4011` (grupo ocupacional), `VD4012` (contribui previdência), `VD4031` (horas semanais)
*   **Renda:** `VD4020` (renda), `VD4019` (renda habitual)
*   **Peso Amostral:** `V1028` (peso)

**Observação:** O notebook aplica um recorte de idade (`16 anos ou mais`) e uma fração da amostra para otimizar o tempo de execução no Colab. O arquivo `.parquet` reflete esses recortes.
