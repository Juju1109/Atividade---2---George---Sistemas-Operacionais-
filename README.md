# Atividade---2---George---Sistemas-Operacionais-
### Questões sobre Ferramentas de Monitoramento de Sistema

1.  **Comparação de Finalidade e Acesso:** Qual a principal diferença na finalidade e na forma de acesso entre o Monitor de Atividade e o `top`? Como o Gerenciador de Tarefas se alinha com essa distinção?

R= O Monitor de Atividade e o Gerenciador de Tarefas são gráficos e fáceis de usar, já o top é em terminal e mais voltado para administradores. O Gerenciador de Tarefas se alinha ao Monitor de Atividade por também ser visual.

2.  **Monitoramento de CPU:** Como você usaria cada uma das três ferramentas para identificar qual processo está consumindo a maior parte da CPU em tempo real? Descreva os passos básicos para cada sistema operacional.

R= No Mac, basta abrir o Monitor de Atividade e ordenar pela aba CPU. No Windows, usa-se o Gerenciador de Tarefas e observa-se a coluna CPU. No Linux, o comando top mostra em tempo real, e a tecla P ordena pelo maior consumo.

3.  **Análise de Memória:** O Monitor de Atividade e o Gerenciador de Tarefas apresentam detalhes sobre o uso de memória (como memória física e swap). Como o `top` em Linux exibe essa informação e quais métricas de memória são mais relevantes para entender o consumo de um processo?

R= O Monitor de Atividade e o Gerenciador de Tarefas mostram a RAM e a swap em gráficos. O top em Linux exibe no cabeçalho o uso de memória. As métricas importantes são: RES (memória real), VIRT (memória virtual) e %MEM.

4.  **Processos e PIDs:** Explique a importância do **PID** (ID do Processo) e como ele é exibido em cada uma das ferramentas. Como você usaria o PID para encerrar um processo que não responde em cada sistema operacional?

R= O PID identifica cada processo. Ele aparece nas três ferramentas e pode ser usado para encerrar programas: no Mac com o botão de encerrar, no Windows em “Finalizar tarefa” e no Linux com kill PID.

5.  **Diferença na Interface:** Descreva as principais diferenças na interface do usuário (UI) entre as três ferramentas. Qual delas é mais orientada a comandos de texto e qual é mais visual?

R= O Monitor de Atividade e o Gerenciador de Tarefas têm interface gráfica, enquanto o top é baseado em texto no terminal.

6.  **Monitoramento de Rede:** Como o Monitor de Atividade e o Gerenciador de Tarefas permitem inspecionar o tráfego de rede de diferentes aplicativos? Qual comando ou técnica similar é usada no Linux para obter informações detalhadas sobre a atividade de rede de processos?

R= O Monitor de Atividade e o Gerenciador de Tarefas têm abas que mostram tráfego de rede por aplicativo. No Linux, usam-se comandos como iftop, nethogs ou netstat.

7.  **Análise de Disco:** O Monitor de Atividade e o Gerenciador de Tarefas possuem abas ou seções dedicadas para monitorar a atividade do disco (leitura/escrita). Qual a importância de monitorar o disco e como o `top` (ou uma ferramenta complementar do Linux) pode ser usado para obter essa mesma informação?

R= No Mac e no Windows existem abas para ver leitura e gravação no disco. Isso é importante, pois processos que usam muito o disco deixam o sistema lento. No Linux, essa função pode ser feita com ferramentas como iotop.

8.  **Hierarquia de Processos:** Em que medida o Monitor de Atividade e o Gerenciador de Tarefas são capazes de exibir a hierarquia de processos (processos pais e filhos)? E como o `top` pode ser configurado ou complementado com outro comando para mostrar essa hierarquia?

R= O Monitor de Atividade e o Gerenciador de Tarefas não exibem bem a relação pai e filho. No Linux, essa hierarquia pode ser vista no htop ou com o comando ps --forest.

9.  **Uso em Servidores vs. Desktops:** Qual das três ferramentas é mais adequada para monitoramento em ambientes de servidor (especialmente sem interface gráfica)? Justifique sua resposta, explicando como as características de cada uma se encaixam melhor em cenários de servidor ou de desktop.

R= O top é ideal para servidores porque funciona no terminal e não precisa de interface gráfica. Já o Monitor de Atividade e o Gerenciador de Tarefas são melhores em desktops por serem gráficos e intuitivos.
