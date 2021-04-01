# Arduino_AC1
## Nossa primeira AC, observe bem o código, procure pelos erros.

Use o FORK para adicionar esse projeto a sua organização antes de começar.

![](https://img.shields.io/github/forks/Leoruiz197/Arduino_AC1)
![](https://img.shields.io/github/stars/Leoruiz197/Arduino_AC1)

![](https://github.com/Bullfrog2RA/Arduino_AC1/blob/main/AC1.png)

## **O PROBLEMA:** 

Nosso grupo foi chamado para que nós fazermos um sistema eletrico em uma fabrica. Nesse sistema elétrico nos tivemos que fazer metodos para manter um cotrole na fabrica.

Entre esses metodos era fazer com que avizasse sobre a temeratura (led azul), luminosidade (led verde) e um botao que ligava e deligava para saber se a producao esta acontecendo ou esta parada (led vermelho)
![](https://github.com/Bullfrog2RA/Arduino_AC1/blob/main/0.png)
![](https://github.com/Bullfrog2RA/Arduino_AC1/blob/main/Leonardo-Buonanno.png)
![](https://github.com/Bullfrog2RA/Arduino_AC1/blob/main/unknown%20(1).png)
![](https://github.com/Bullfrog2RA/Arduino_AC1/blob/main/unknown%20(2).png)
![](https://github.com/Bullfrog2RA/Arduino_AC1/blob/main/unknown%20(3).png)
![](https://github.com/Bullfrog2RA/Arduino_AC1/blob/main/unknown%20(4).png)
![](https://github.com/Bullfrog2RA/Arduino_AC1/blob/main/unknown.png)
### Funcionalidades esperadas:

- Um botão para ligar e outro para desligar a produção indicados pelo led vermelho.
- Leitura do sensor de temperatura e teste, ao atingir **15℃** o led azul deve acender, deve ser informado via serial e somente apagar o led quando a temperatura for mais baixa que isso.
- Leitura do sensor de luminosidade e teste, ao indicar um valor acima de **5** a luminosidade do ambiente esta muito alta, deve ser informado via serial e o led verde deve permanecer aceso até a luminosidade diminuir.

### Composição da nota do grupo
- Ajuste dos erros no código principal.
- Documentação do projeto do github no README.md abordando todos os pontos necessários.
- No README.md adicionando nome do grupo fotos e short bio de cada integrante.
- Todos os pontos do código devem estar comentados corretamente informando o que se passa ali.
- Usar do Serial o max possível, sempre informando os estados da produção e demais itens.
- Implementação das funcionalidades faltantes.

### Desconto de nota individual

**Caso um dos integrantes venha a ter um desempenho inconsistente na colaboração com o projeto em comparação com os demais da equipe o mesmo pode ter sua nota parcial ou total descontada.**

#### LINKS UTEIS:

- **Funções:** https://www.arduino.cc/reference/pt/
- **map():** https://www.arduino.cc/reference/pt/language/functions/math/map/
- **millis():** https://www.arduino.cc/reference/pt/language/functions/time/millis/

- **Editor de README.md:** https://pandao.github.io/editor.md/en.html
- **Shield.io:** https://shields.io/
