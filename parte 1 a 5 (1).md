1 e 2\_



Requisitos Funcionais



1\_ o sistema deve calcular quantos pacientes tem na UPA atual

2\_o sistema deve ser integrado ao google maps

3\_o sistema deve ter integração com uma IA

4\_o sistema precisa ter login e cadastro

5\_o sistema precisa ter integração com o gov

6\_o sistema precisa fazer calculos para otimizar rotas utilizando o google maps

7\_o sistema deve ser alinhado ao sistema do recepcionista

8\_o sistema deve avisar a outra UPA que o paciente POSSIVELMENTE está vindo

9\_o sistema deve classificar o problema do usuário para dar niveis de risco

10\_o sistema deve calcular o tempo de espera com base em seu risco, sua localização atual e o tempo da fila.



Regras De Negócios



1\_O sistema tem que ser justo

2\_O sistema tem que ser eficaz

3\_O sistema deve aumentar a estimativa de vida, ou melhorar o respeito do povo pelo sistema de UPAs

4\_O sistema deve ser acessivel

5\_O sistema tem que ser simples e compreensível



Persona



Nome:Sérgio Rodrigo da Silva

idade:53 anos

Problema:está com uma espera muito grande em sua UPA



3\_



Como \[tipo de usuário], quero \[ação ou necessidade], para \[benefício esperado]



A01: Como paciente, quero conseguir fazer o login usando minha conta gov, para acessar o site

A02: Como paciente, quero confirmar meu deslocamento, para a UPA saber que estou a caminho

A03: Como paciente, quero verificar a rota mais rapida, para evitar transito ou problemas diversos

A04: Como paciente, quero que o site mantenha minha sessão salva, para economizar tempo

A05: Como recepcionista, quero poder avisar ao sistema que um paciente novo chegou, para deixar o sistema alinhado a realidade



4\_



A01: Teste se o site disponibiliza o login, e ele leva diretamente para o site do governo de login, e de nenhuma forma consiga acessar a área principal do site (onde pode ser usado as funcionalidades) sem login.



A02: Confirmar se o sistema da upa avisa o recepcionista quando o paciente chega no ponto pelo mapa e se avisa quando o usuário aperta em "começar rota"



A03: Verificar se está integrado de maneira certa o sistema de calculo com o google maps, e se o google maps está levando o usuário ao local certo (realiza ao mínimo 25 testes com lugares diversos de partida e upas diferentes de chegada)



A04: Verifique nos navegadores google, chrome, safari (iphone) e o brave pra verificar se todos esses navegadores estão guardando certo o login



A05: veja se o sistema aumenta o número de pacientes quando o recepcionista avisa ao sistema que chegou novo paciente (teste 15 vezes)



5\_



A01: Como paciente, quero conseguir fazer o login usando minha conta gov, para acessar o site

|**ID**|**História de Usuário (HU)**|**Critérios de Aceitação**|**Prioridade**|
|-|-|-|-|
|A01|Como paciente, quero conseguir fazer o login usando minha conta gov, para acessar o site|1\_Teste se o site disponibiliza o login, e ele leva diretamente para o site do governo de login<br /><br />2\_O site principal onde as funcionalidades estão possíveis de ser usadas não pode ser acessado sem login|Alta|
|A02|Como paciente, quero confirmar meu deslocamento, para a UPA saber que estou a caminho|1\_ Confirmar se o sistema da upa avisa o recepcionista quando o paciente chega no ponto pelo mapa<br /><br />2\_ Confirmar se o sistema da upa também é avisado a partir do momento que o usuário começa a rota|Média|
|A03|Como paciente, quero verificar a rota mais rapida, para evitar transito ou problemas diversos|1\_Verificar se está integrado de maneira certa o sistema de calculo com o google maps<br /><br />2\_Verificar se o google maps está levando o usuário ao local certo (realiza ao mínimo 25 testes com lugares diversos de partida e upas diferentes de chegada)|Alta|
|A04|Como paciente, quero que o site mantenha minha sessão salva, para economizar tempo|1\_Verifique nos navegadores google, chrome, safari (iphone) e o brave pra verificar se todos esses navegadores estão guardando certo o login|Baixa|
|A05|Como recepcionista, quero poder avisar ao sistema que um paciente novo chegou, para deixar o sistema alinhado a realidade|1\_veja se o sistema aumenta o número de pacientes quando o recepcionista avisa ao sistema que chegou novo paciente (teste 15 vezes)|Alta|



