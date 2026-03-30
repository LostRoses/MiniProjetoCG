Relógio Analógico com Calendário 

Este projeto implementa um relógio analógico interativo em HTML5 Canvas, com ponteiros de hora, minuto e segundo, além de um calendário embutido e um botão para alterar a cor de fundo. 

Funcionalidades 

Relógio analógico: mostra horas, minutos e segundos em tempo real. 

Calendário: exibe o dia e mês atuais em um pequeno retângulo dentro do mostrador. 

Interatividade: 

Clique no calendário para alternar sua posição (direita/esquerda). 

Clique no botão "Cor" para mudar a cor de fundo do relógio. 

Animação: atualização contínua usando requestAnimationFrame. 

Transformações gráficas utilizadas 

Translação (ctx.translate): centraliza o relógio no canvas e posiciona o calendário. 

Rotação (ctx.rotate): gira os ponteiros conforme o tempo. 

Escala (ctx.scale): aumenta o calendário em 20% para destacar. 

Composição de transformações: combina translação + rotação nos ponteiros e translação + escala no calendário. 

Rotação com ponto fixo: ponteiros giram em torno do centro do relógio. 

Save/Restore (ctx.save/ctx.restore): garante que cada transformação afete apenas o elemento desejado. 

Estrutura do código 

desenharRelogio(): função principal que desenha o relógio e atualiza a cada frame. 

desenharPonteiro(): desenha cada ponteiro com rotação. 

desenharNumeros(): posiciona os números 1 a 12 ao redor do mostrador. 

desenharMarcas(): desenha as 60 marcas de minutos/segundos. 

desenharCalendario(): mostra o dia/mês atual, com translação e escala. 

desenharBotao(): desenha o botão "Cor". 

Eventos de clique: controlam a interação com calendário e botão. 

Conclusão 

Este projeto demonstra o uso de transformações gráficas e animação em Canvas, atendendo a todos os requisitos: translação, rotação, escala, composição de transformações, rotação com ponto fixo, animação e gerenciamento de estados. 

 
