
# Testes automatizados + Curso completo de teste de software - Udemy 5h - 06/04/2020
  
**O que é teste de software?**  
Testar é verificar se a funcionalidade está atendendo corretamente, se tem o comportamento esperado e considerado correto, verificar para garantir que está funcionando da forma correta. Ex: testar a troca de marcha de uma bicicleta, apertar o botão do controle da televisão para ligá-la.  
  
  
## Verdades sobre o teste de software  
  
- Testes não verificam todas as possibilidades, pois as entradas (testes) são infinitas;  
- Não garante qualidade (ex: bolsa, depende da necessidade do usuário);  
- Testes custam de 20% a 30% do total da elaboração de um software.  
  
  
## Perfil dos testadores  
  
O perfil de um testador de software é detalhista, paciente, focado, motivado, criterioso, perspicaz e pessimista com respeito a funcionalidade do sistema.  
Deve ter uma visão de qualidade e crítica.  
  
- Elaborar testes relevantes;  
- Ser referência de critério e qualidade;  
- Executar os testes no tempo planejado.  
  
## Níveis de teste  
  
**Teste de unidade:** testa a menor parte do sistema (mais baixa), teste realizado pelo programador;  
**Teste de integração:** envolve componentes do sistema, testar a integração/comunicação entre esses componentes, teste realizado pelo programador;  
**Teste de sistema:** executar o software como se fosse um usuário final, mas com visão de testador procurando falhas, baseado no documento do sistema, teste realizado pelo tester;  
**Teste de aceitação:** é o usuário que testa e avalia (ambiente de homologação), se o cliente aceita ou não o sistema;  
**Teste Alfa:** semelhante ao teste de aceitação, porem deve-se disponibilizar o sistema para mais pessoas. Usa-se o sistema e dá o feedback e fica uma equipe junto para tirar dúvidas e fazer os ajustes;  
**Teste Beta:** grande número de pessoas, os testes não são planejados, ex: jogos (pré-lançamento). Os usuários reportam os erros e as melhorias.  
**Teste de regressão:** pode ser realizado a qualquer momento. Geralmente é realizado o teste após alguma alteração de funcionalidade, deve-se detectar efeitos colaterais, pois pode afetar outras partes do sistema.  
  
## Técnicas de teste  
  
**Caixa branca:** vejo o interior do sistema, verifica a estrutura do código.  
**Caixa preta:** só entradas e saídas (dou entrada no sistema - ex: inserir os dados de login e senha e aperta em ok e a saída é o login sendo efetuado no sistema).  
**Análise estática:** serve para verificar se as boas práticas de programação estão sendo colocadas em prática, ou seja, não precisa rodar o sistema, pois analisa e verifica o código. Ex: se está documentado, se tem tratamento de exceções, se fecha a conexão após utilizá-la.  
  
## Testes manuais x testes automáticos  
  
*Teste manual:* alguém executa manualmente;  
*Teste automático:* são códigos usados para testar o sistema, demora um pouco mais para ser criado, porém pode-se fazer várias vezes.  
  
## Teste estático x teste dinâmico  
  
Teste estático: verifica o código, se estão sendo aplicadas as boas práticas de programação, é aconselhável ter na empresa um check-list das perguntas.  
Teste dinâmico: executa o sistema para testar. Executa o sistema, insere uma entrada e confere a saída.  
  
As duas formas de teste se complementam.  
  
Dica: após o programador terminar o código, é interessante ter alguém para revisar.  
  
## Tipos de teste  
  
Funcionalidade: validar se as funções do sistema estão funcionando corretamente. Envolve: unidade, integração, sistema, etc.  
  
Desempenho: tempo de resposta do desempenho do sistema. Ex: upload de uma foto no Facebook (tempo limite). Ferramenta JMeter.  
  
Usabilidade: envolvem os aspectos de experiência do usuário, ex: cores, se é agradável usar o sistema.  
  
Segurança: testes que validam a proteção, criptografadas. Algumas empresas chegam a contratar hackers para tentar invadir o sistema.  
  
Portabilidade: testar o funcionamento do sistema em várias plataformas e dispositivos, ex: Windows, Linux, versões disponíveis.  

Stress: testar em condições extremas, ex: acesso de milhares de usuários e verificar se o sistema está correspondendo.

## Etapas de desenvolvimento e de teste

Teste de sistema: gerenciamento de teste de sistema (planilha);
Teste de aceitação: teste feito pelo cliente, se estiver de acordo com o que ele solicitou (planilha de teste de aceitação). O teste de aceitação deve estar de acordo com o requisito (resultado esperado).
Testes Alfa e Beta: os testes não são planejados (planilha de gerenciar teste Alfa e Beta).

## Boas práticas de teste de software

Boas práticas não técnicas: pessoas que não participa do codificação do sistema. "O que não está especificado, não será validado"

- Seleção de cenários:
		- tempo para execução dos testes;
		- maturidade do testador;
		- seja pessimista;
		- registre as falhas encontradas;

Boas práticas técnicas: não se limite aos cenários planejados, pois tem a possibilidade de explorar, se achou uma falha, detalhe ao máximo. Se a falha foi corrigida, reteste. Busque padrões ao reportar uma falha, ex: se o erro está ocorrendo associado a penas "tal produto" ou se envolve o produto da mesma cor.

 - Ferramentas para controle:
		 - Buzzila
		 - Tack
		 - Jira

## Técnicas

Teste sempre os valores limites.Ex: idade fora do intervalo 18 - 55 e colocar a idade de 17 anos.

Formulários: campo em branco, campo com valor inválido, e-mail inválido, quantidade de caracteres, mensagens de erro coerentes.
Cálculos: valores positivos, valores negativos, zero, intervalos fechados ou abertos, acima do limite máximo, abaixo do limite mínimo.

    Tente pensar como o usuário pensaria.

## Certificações

www.istqb.org
www.alats.org.br
