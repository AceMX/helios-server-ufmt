# Sobre o e-Votação

Implantado em 2020, o e-Votação utiliza o [Helios Voting](https://heliosvoting.org) como motor, que permite a realização de eleições por meio da Internet com
auditoria aberta ao público (End-to-end voter verifiable – E2E), podendo ser acessado em qualquer computador ou dispositivo móvel conectado à internet.

O Sistema Eletrônico on-line Helios Voting é disponibilizado publicamente como software livre e possui as seguintes características:

- sigilo: garante o sigilo do voto, não permitindo que a escolha de um eleitor (seu voto) seja revelada
- privacidade: garante a criptografia dos votos antes do envio, de maneira que não seja possível a identificação do voto posteriormente
- rastreabilidade: fornece, para cada eleitor, um número rastreável de seu voto, permitindo a checagem, por ele, se o voto foi depositado corretamente
- integridade dos dados: permite que os votos não sejam alterados ou excluídos por terceiros, em virtude do uso de criptografia
- apuração dos votos: permite a apuração dos votos de maneira automática ou manual
- comprovação: permite auditoria



## Como solicitar a votação online

A solicitação deve ser formalizada à STI-CES via Processo SEI.
Ela deve estar acompanhada do:

* ato normativo com a constituição da comissão
* ato normativo com a aprovação da consulta, com previsão da votação online
* lista dos cargos concorridos
* lista dos candidatos(as), com as inscrições deferidas pelo presidente da comissão, na ordem em que devem figurar nas urnas
* lista dos eleitores aptos a votarem, separados por categoria, informando nome completo, endereço de e-mail, número do CPF e matrícula SIAPE ou RGA (a depender da categoria)
* período de duração da votação online

## Urnas

Cada link gerado para votação representa uma urna. Cada urna tem apenas uma categoria de votante, ex.: urna 01 tem apenas docentes, urna 02 tem apenas discentes e urna 03 tem apenas técnicos.

Não é possível a implementação de pesos nos votos. Após o fechamento e apuração, cada urna apresentará o resultado simples dos votos, cabendo a comissão realizar os devidos calculos.

Opção|Votos
--|--
Candidato 1 | 10
Candidato 2 | 15
Candidato 3 | 20

## Quem pode votar

Qualquer pessoa previamente informada pela comissão pode votar. Existe apenas uma diferença em como essa pessoa realizará sua autenticação para o depósito do voto.

Grupo 1: Servidores técnico-administrativos e docentes atívos, estudantes de graduação presencial regularmente matriculados e estudantes de pós-graduação stricto sensu regularmente matriculados
votam usando o CPF e a mesma senha de acesso do [Portal de Sistemas Integrados](https://sistemas.ufmt.br/ufmt.portalsistemas).

Grupo 2: Estudantes ativos de EaD, estudantes lato sensu (presencial ou à distância) e docentes externos (sem vínculo com a UFMT) votam usando o CPF e uma senha gerada pelo Sistema e-Votação.
Essa senha é unica e encaminhada apenas para o votante.

**Atenção:**

* Se existirem votantes de ambos os grupos, será necessário a criação de urnas separadas para cada grupo.

## Suporte no dia da votação

## Acompanhamento do processo de votação

O Helios permite o acompanhamento por qualquer pessoa. Um teste pode ser feito acessando o endereço <https://evotacao.ufmt.br/helios/e/cba-tae-teste-2020_21>.
Clicando em Eleitores & Cédulas é possível ver a lista de votantes e seus respectivos localizadores de votos e clicando em Questões é possível confirmar as opções de votos cadastradas.
Além disso, caso seja do interesse da comissão, a CES pode realizar uma transmissão via https://conferenciaweb.rnp.br do procedimento de fechamento das urnas e da apuração do resultado.