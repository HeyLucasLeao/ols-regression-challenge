# Variáveis

## Identificação e Notificação

- **NU_NOTIFIC**: Número do registro. Campo Interno. Número sequencial gerado automaticamente pelo sistema.
- **DT_NOTIFIC**: Data do preenchimento da ficha de notificação. Campo Obrigatório. Formato: DD/MM/AAAA.
- **SEM_NOT**: Semana Epidemiológica do preenchimento da ficha de notificação. Campo Interno. Calculado a partir da data dos Primeiros Sintomas.
- **DT_SIN_PRI**: Data de 1ºs sintomas. Campo Obrigatório. Formato: DD/MM/AAAA.
- **SEM_PRI**: Semana Epidemiológica dos Primeiros Sintomas. Campo Interno. Calculado a partir da data dos Primeiros Sintomas.

## Localização

- **SG_UF_NOT**: Unidade Federativa onde está localizada a Unidade que realizou a notificação. Campo Obrigatório.
- **CO_MUN_NOT**: Município onde está localizada a Unidade que realizou a notificação. Campo Obrigatório.
- **CO_REGIONA**: Regional de Saúde onde está localizado o Município que realizou a notificação. Campo Interno.
- **CO_UNI_NOT**: Unidade que realizou o atendimento, coleta de amostra e registro do caso. Campo Obrigatório.

## Identificação do Paciente

- **TEM_CPF**: Informar se o paciente notificado dispõe de CPF. Campo Obrigatório.
- **NU_CPF**: Número do CPF do paciente. Campo Obrigatório.
- **ESTRANG**: Informar se o paciente é estrangeiro. Campo Obrigatório.
- **NU_CNS**: Número do Cartão Nacional de Saúde do paciente. Campo Obrigatório.
- **NM_PACIENT**: Nome completo do paciente. Campo Obrigatório.
- **CS_SEXO**: Sexo do paciente. Campo Obrigatório. Valores: 1-Masculino, 2-Feminino, 9-Ignorado.
- **DT_NASC**: Data de nascimento do paciente. Campo Essencial.
- **NU_IDADE_N**: Idade informada pelo paciente. Campo Obrigatório.
- **TP_IDADE**: Tipo/Idade. Campo Obrigatório. Valores: 1-Dia, 2-Mês, 3-Ano.
- **CS_GESTANT**: Idade gestacional da paciente. Campo Obrigatório para sexo feminino.
- **CS_RACA**: Cor ou raça declarada pelo paciente. Campo Obrigatório. Valores: 1-Branca, 2-Preta, 3-Amarela, 4-Parda, 5-Indígena, 9-Ignorado.
- **CS_ETINIA**: Nome e código da etnia do paciente, quando indígena. Campo Essencial.
- **POV_CT**: Informar se o paciente é membro de algum povo ou comunidade tradicional. Campo Obrigatório.
- **TP_POV_CT**: Informar o povo ou comunidade tradicional. Campo Obrigatório.
- **CS_ESCOL_N**: Nível de escolaridade do paciente. Campo Essencial.
- **PAC_COCBO**: Ocupação profissional do paciente. Campo Essencial.
- **NM_MAE_PAC**: Nome completo da mãe do paciente. Campo Essencial.

## Endereço do Paciente

- **NU_CEP**: CEP de residência do paciente. Campo Essencial.
- **SG_UF**: Unidade Federativa de residência do paciente. Campo Obrigatório.
- **CO_MUN_RES**: Município de residência do paciente. Campo Obrigatório.
- **NM_BAIRRO**: Bairro de residência do paciente. Campo Essencial.
- **NM_LOGRADO**: Logradouro do endereço de residência. Campo Essencial.
- **NU_NUMERO**: Número do endereço. Campo Essencial.
- **NM_COMPLEM**: Complemento do logradouro. Campo Essencial.
- **NU_DDD_TEL**: Código DDD do telefone para contato. Campo Essencial.
- **NU_TELEFON**: Número de telefone para contato. Campo Essencial.
- **CS_ZONA**: Zona geográfica do endereço. Campo Essencial. Valores: 1-Urbana, 2-Rural, 3-Periturbana, 9-Ignorado.
- **CO_PAIS**: País de residência do paciente. Campo Obrigatório.

## Sinais e Sintomas

- **FEBRE**: Paciente apresentou febre? Campo Essencial.
- **TOSSE**: Paciente apresentou tosse? Campo Essencial.
- **GARGANTA**: Paciente apresentou dor de garganta? Campo Essencial.
- **DISPNEIA**: Paciente apresentou dispneia? Campo Essencial.
- **DESC_RESP**: Paciente apresentou desconforto respiratório? Campo Essencial.
- **SATURACAO**: Paciente apresentou saturação O2 < 95%? Campo Essencial.
- **DIARREIA**: Paciente apresentou diarreia? Campo Essencial.
- **VOMITO**: Paciente apresentou vômito? Campo Essencial.
- **DOR_ABD**: Paciente apresentou dor abdominal? Campo Essencial.
- **FADIGA**: Paciente apresentou fadiga? Campo Essencial.
- **PERD_OLFT**: Paciente apresentou perda do olfato? Campo Essencial.
- **PERD_PALA**: Paciente apresentou perda do paladar? Campo Essencial.
- **OUTRO_SIN**: Paciente apresentou outro(s) sintoma(s)? Campo Essencial.
- **OUTRO_DES**: Listar outros sinais e sintomas. Campo Essencial.

## Fatores de Risco

- **FATOR_RISC**: Paciente apresenta algum fator de risco? Campo Essencial.
- **PUERPERA**: Paciente é puérpera? Campo Essencial.
- **CARDIOPATI**: Paciente possui doença cardiovascular crônica? Campo Essencial.
- **HEMATOLOGI**: Paciente possui doença hematológica crônica? Campo Essencial.
- **SIND_DOWN**: Paciente possui Síndrome de Down? Campo Essencial.
- **HEPATICA**: Paciente possui doença hepática crônica? Campo Essencial.
- **ASMA**: Paciente possui asma? Campo Essencial.
- **DIABETES**: Paciente possui diabetes mellitus? Campo Essencial.
- **NEUROLOGIC**: Paciente possui doença neurológica crônica? Campo Essencial.
- **PNEUMOPATI**: Paciente possui outra pneumopatia crônica? Campo Essencial.
- **IMUNODEPRE**: Paciente possui imunodeficiência ou imunodepressão? Campo Essencial.
- **RENAL**: Paciente possui doença renal crônica? Campo Essencial.
- **OBESIDADE**: Paciente possui obesidade? Campo Essencial.
- **OBES_IMC**: Valor do IMC do paciente. Campo Essencial.
- **OUT_MORBI**: Paciente possui outro(s) fator(es) de risco? Campo Essencial.
- **MORB_DESC**: Listar outro(s) fator(es) de risco. Campo Essencial.

## Vacinação

- **VACINA_COV**: Paciente recebeu vacina COVID-19? Campo Obrigatório.
- **DOSE_1_COV**: Data da 1ª dose da vacina COVID-19. Campo Essencial.
- **DOSE_2_COV**: Data da 2ª dose da vacina COVID-19. Campo Essencial.
- **DOSE_REF**: Data da dose reforço da vacina COVID-19. Campo Essencial.
- **DOSE_2REF**: Data da 2ª dose reforço da vacina COVID-19. Campo Essencial.
- **FAB_COV1**: Fabricante da 1ª dose da vacina COVID-19. Campo Essencial.
- **FAB_COV2**: Fabricante da 2ª dose da vacina COVID-19. Campo Essencial.
- **FAB_COVRF**: Fabricante da dose reforço da vacina COVID-19. Campo Essencial.
- **FAB_COVRF2**: Fabricante da 2ª dose reforço da vacina COVID-19. Campo Essencial.
- **LOTE_1_COV**: Lote da 1ª dose da vacina COVID-19. Campo Essencial.
- **LOTE_2_COV**: Lote da 2ª dose da vacina COVID-19. Campo Essencial.
- **LOTE_REF**: Lote da dose reforço da vacina COVID-19. Campo Essencial.
- **LOTE_REF2**: Lote da 2ª dose reforço da vacina COVID-19. Campo Essencial.
- **FNT_IN_COV**: Fonte dos dados sobre a vacina COVID-19. Campo Interno.

## Tratamento

- **ANTIVIRAL**: Paciente usou antiviral para gripe? Campo Essencial.
- **TP_ANTIVIR**: Qual antiviral utilizado? Campo Essencial.
- **OUT_ANTIV**: Outro antiviral utilizado. Campo Essencial.
- **DT_ANTIVIR**: Data do início do tratamento com antiviral. Campo Essencial.
- **TRAV_COV**: Paciente recebeu tratamento antiviral para COVID-19? Campo Essencial.
- **TIPO_TRAV**: Qual antiviral para COVID-19 utilizado? Campo Essencial.
- **OUT_TRAV**: Outro antiviral para COVID-19 utilizado. Campo Essencial.
- **DT_TRAV_COV**: Data do início do tratamento com antiviral para COVID-19. Campo Essencial.

## Internação

- **HOSPITAL**: Paciente foi internado? Campo Essencial.
- **DT_INTERNA**: Data da internação por SRAG. Campo Obrigatório.
- **SG_UF_INTE**: Unidade Federativa de internação. Campo Essencial.
- **CO_MU_INTE**: Município de internação. Campo Essencial.
- **CO_UN_INTE**: Unidade de Saúde de internação. Campo Essencial.
- **UTI**: Paciente foi internado em UTI? Campo Essencial.
- **DT_ENTUTI**: Data da entrada na UTI. Campo Essencial.
- **DT_SAIDUTI**: Data da saída da UTI. Campo Essencial.
- **SUPORT_VEN**: Uso de suporte ventilatório. Campo Essencial.

## Exames

- **RAIOX_RES**: Resultado de Raio X de Tórax. Campo Essencial.
- **RAIOX_OUT**: Outro resultado de Raio X de Tórax. Campo Essencial.
- **DT_RAIOX**: Data do Raio X. Campo Essencial.
- **TOMO_RES**: Resultado da tomografia. Campo Essencial.
- **TOMO_OUT**: Outro resultado da tomografia. Campo Essencial.
- **DT_TOMO**: Data da tomografia. Campo Essencial.
- **AMOSTRA**: Foi realizada coleta de amostra? Campo Essencial.
- **DT_COLETA**: Data da coleta da amostra. Campo Essencial.
- **TP_AMOSTRA**: Tipo de amostra coletada. Campo Essencial.
- **OUT_AMOST**: Outro tipo de amostra coletada. Campo Essencial.

## Testes Laboratoriais

- **RES_AN**: Resultado do Teste Antigênico. Campo Essencial.
- **POS_AN_FLU**: Teste Antigênico positivo para influenza? Campo Essencial.
- **TP_FLU_AN**: Tipo de influenza detectado no Teste Antigênico. Campo Essencial.
- **POS_AN_OUT**: Teste Antigênico positivo para outros vírus? Campo Essencial.
- **AN_SARS2**: Teste Antigênico positivo para SARS-CoV-2. Campo Essencial.
- **AN_VSR**: Teste Antigênico positivo para VSR. Campo Essencial.
- **AN_PARA1**: Teste Antigênico positivo para Parainfluenza 1. Campo Essencial.
- **AN_PARA2**: Teste Antigênico positivo para Parainfluenza 2. Campo Essencial.
- **AN_PARA3**: Teste Antigênico positivo para Parainfluenza 3. Campo Essencial.
- **AN_ADENO**: Teste Antigênico positivo para Adenovirus. Campo Essencial.
- **AN_OUTRO**: Teste Antigênico positivo para outro vírus respiratório. Campo Essencial.
- **DS_AN_OUT**: Descrição do outro vírus respiratório detectado. Campo Essencial.

### RT-PCR

- **PCR_RESUL**: Resultado da RT-PCR. Campo Essencial.
- **DT_PCR**: Data do resultado da RT-PCR. Campo Essencial.
- **POS_PCRFLU**: RT-PCR positivo para influenza? Campo Essencial.
- **TP_FLU_PCR**: Tipo de influenza detectado na RT-PCR. Campo Essencial.
- **PCR_FLUASU**: Subtipo para Influenza A detectado na RT-PCR. Campo Essencial.
- **FLUASU_OUT**: Outro subtipo para Influenza A. Campo Essencial.
- **PCR_FLUBLI**: Linhagem para Influenza B detectada na RT-PCR. Campo Essencial.
- **FLUBLI_OUT**: Outra linhagem para Influenza B. Campo Essencial.
- **POS_PCROUT**: RT-PCR positivo para outros vírus? Campo Essencial.
- **PCR_SARS2**: RT-PCR positivo para SARS-CoV-2. Campo Essencial.
- **PCR_VSR**: RT-PCR positivo para VSR. Campo Essencial.
- **PCR_PARA1**: RT-PCR positivo para Parainfluenza 1. Campo Essencial.
- **PCR_PARA2**: RT-PCR positivo para Parainfluenza 2. Campo Essencial.
- **PCR_PARA3**: RT-PCR positivo para Parainfluenza 3. Campo Essencial.
- **PCR_PARA4**: RT-PCR positivo para Parainfluenza 4. Campo Essencial.
- **PCR_ADENO**: RT-PCR positivo para Adenovirus. Campo Essencial.
- **PCR_METAP**: RT-PCR positivo para Metapneumovirus. Campo Essencial.
- **PCR_BOCA**: RT-PCR positivo para Bocavirus. Campo Essencial.
- **PCR_RINO**: RT-PCR positivo para Rinovirus. Campo Essencial.
- **PCR_OUTRO**: RT-PCR positivo para outro vírus respiratório. Campo Essencial.
- **DS_PCR_OUT**: Descrição do outro vírus respiratório detectado. Campo Essencial.

## Encerramento do Caso

- **CLASSI_FIN**: Classificação final do caso. Campo Obrigatório.
- **CLASSI_OUT**: Descrição de outro agente etiológico identificado. Campo Obrigatório.
- **CRITERIO**: Critério de encerramento. Campo Essencial.
- **EVOLUCAO**: Evolução do caso. Campo Essencial.
- **DT_EVOLUCA**: Data da alta ou óbito. Campo Essencial.
- **DT_ENCERRA**: Data do encerramento do caso. Campo Obrigatório.
- **NU_DO**: Número da Declaração de Óbito. Campo Essencial.

## Observações e Profissional de Saúde

- **OBSERVA**: Outras observações sobre o paciente. Campo Opcional.
- **NOME_PROF**: Nome do profissional de saúde responsável pela notificação. Campo Essencial.
- **REG_PROF**: Número do conselho ou matrícula do profissional de saúde. Campo Essencial.
- **DT_DIGITA**: Data de inclusão do registro no sistema. Campo Interno.