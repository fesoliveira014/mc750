# Revisão pra IHC

## Slide 01 - Usabilidade 1

- Por que devemos nos importar sobre a interface de usuário de um software?
    
    A interface de usuário afeta bastante a percepção do software

    + Sotware usável vende melhor
    + Web sites ruins de usar são abadonados

    A percepção às vezes é superficial

    + Usuários se culpam por falhas da UI
    + Pessoas que compram o software nem sempre são o usuário final

- O custo de errar no design
    + Tempo do usuário não está ficando mais barato
    + Faça o design correto agora ou pague por isso mais tarde
    + Disastres podem acontecer:
        * Máquina de radiação...

- Interfaces não são faceis de projetar
    + Você não é o usuário. A maior parte da engenharia de software envolve falar com outros programadores, mas a interface é sobre se comunicar com o usuário
    + O usuário sempre está certo. Problemas de consistência são culpa do sistema
    + Mas o usuário nem sempre está certo ao mesmo tempo, pois não são designers.

- Definição de usabilidade
    + Usabilidade: quão bem usuários podem usar uma funcionalidade do sistema.
    + Dimensões de usabilidade:
        * Aprendizado: o quão fácil é aprender a usar?
        * Eficiência: uma vez aprendido, quão rápido se pode usar?
        * Visibilidade: O estado do sistema é visível?
        * Erros: os erros são recuperáveis?
        * Satisfação: a interface é agradável de usar?
    + Podemos quantificar todas essas medidas de usabilidade.

- As dimensões não são uniformes para todas as classes de usuários ou aplicações
    + Depende do usuário
        * Novos usuários precisam de aprendizado, enquanto usuários infrequentes precisam de interfaces memorizáveis e usuários experiêntes precisam de eficiência.
    + Mas nenhum usuário é uniformemente novato ou experiente
        * Depende da experiência do domínio, aplicação e característica

- Experiência do usuário
    + Uma abordagem holística de como o usuário se relaciona com a interface e também de como funciona o relacionamento com o sistema e produto da qual aquela interface faz parte

## Slide 2 - Introdução à IHC

Interação homem-computador é uma disciplina preocupada com o design, avaliaçào e implementação de sistemas interativos de computadores para uso humano e com o estudo de fenômenos que acompanham o uso.

Aspéctos do lado humano da IHC mudam mais devagar, se mudam ao todo. Muito do que se aprendeu sobre nossos processos perceptuais, cognitivos, sociais e emotivos quando interagimos com tecnologias mais velhas se aplicam à interação com tecnologias emergentees do mesmo modo.

Algumas visões e protótipos foram rapidamente convertidos a uma grande gama de aplicações, enquanto outras levaram décadas e algumas permanecem inutilizadas. Entendendo as razões de resultados diferentes, podemos avaliar as visões de hoje de modo mais realístico.

- Base
    + Fatores humanos / ergonomia
    + Sistemas / Ciência da informação
    + Ciência da computação
    + Tornar o uso de ferramentas mais eficiente e achar maneiras de representar e distribuir informação rapidamente

- Evolução do IHC
    + Década de 70
        * A meta era motivar desenvolvedores a considerar a características do ser humano e gerar uma abordagem comportamental para entender design de software, programação e uso de sistemas
        * Assumia-se a validade do modelo cascata
        * Verifica usabilidade depois do sistema ser desenvolvido
        * Problemas: modelo cascata é inviável e o usuário demonstra pouco entendimento da interface
    + Década de 80
        * Abordagem empírica ao design industrial
        * Prototipação no início
        * Envolvimento de usuários reais
        * Desenvolvimento em ciclos de iteração e prototipação para clarificar o problema de design
    + Década de 90
        * Em 1988 IHC faz parte das 9 áreas centrais da Ciência da Computação
        * em 1991 se recomenda a inclusão de IHC nos currículos de CC
        * Em 1997 é incluída no Handbook
        * Departamentos de CC incluem IHC como área de pesquisa
        * O tipo de desenvolvimento passa a ser guiado por objetos mensuráveis, as especificações de usabilidade
        * Design participativo, contextual, etnográfico (comportamental)
        * Design Rationale: processo de tornar explícitos os processos e resultados de design, como a motivação, requisitos, discussões, debates, negociações e decisões
    + Anos 2000 - 2010
        * Novos paradigmas
        * Novas tecnologias

- A importância do IHC é resultado de:
    + Acesso mais barato a computadores significa que pessoas são mais importantes que máquinas
    + Idéias excelentes de interface modeladas a partir de necessidades dos humanos em vez das do sistema
    + Evolução das ideias em um produto através de algumas gerações
    + As pessoas não mais aceitam produtos com interfaces pobres 

## Slide 3 - ReDesign

- Comparação de abordagem entre um design gráfico e um programador na hora de realizar um redesign de uma interface:
    + Quais áreas da interface foram analisadas?
    + Quais foram os problemas percebidos?
    + Que caminhos tomaram para resolvê-los?
    A comparação foi realizada em três critérios:
        * **Usabilidade**: usuários podem facilmente interagir com a interface para conseguir a informação desejada?
        * **Funcionalidade**: que funções e controles estão disponíveis para permitir uso otimizado dos dados?
        * **Comunicação e visual estética**: como a aparência visual e localização espacial dos elementos da interface otimizam funcionalidade?

- Análise do Designer:
    + Assume a funcionalidade dada e o tipo de aplicação do software
    + Assume as restrições de interface do ambiente de execução (SO)
    + Tenta ver como interfaces existentes podem ser melhoradas
    + Inicia _criticando_ a interface, imaginando diferentes cenários de usuários interagindo com a aplicação pela primeira vez:
        * O que um botão faz?
        * Como ver os dados de outra maneira?
        * Etc..

- Análise do Programador:
    + Não realizou anaálise dos elementos da interface original nem a consistência com _guidelines_
    + Descartou a interface complentamente, assumindo que não satisfazia as necessidades do usuário
    + Re-desenhou o problema baseado nas próprias necessidades, propondo um design alternativo

- Lições:
    + Ambos tentaram abordar um ponto de vista do usuário
        * Há três caminhos:
            - O designer se considera um usuário em potecial
            - O designer simula usuários potenciais
            - Se realiza teste com usuários reais
    + O design pela crítica permite focalizar aspéctos de usabilidade e consistência, o que é bom quando há restrição no tempo de design e integridade funcional da aplicação, mas torna difícil de corrigir problemas de funcionalidede

## Slide 4 - Usabilidade 2

- Definição: O tanto quanto um produto pode ser usado por um usuário para alcançar objetovos com eficácia e satisfação em um contexto de uso especificado.

- Metas de usabilidade:
    + Facilidade de aprendizado
    + Eficiência de uso
    + Facilidade de retorno
    + Freqüência de erros
    + Satisfação subjetiva

- Engenharia de Usabilidade
    + Confiar na experiência do designer, em padrões, guidelines ou metodologias racionais e analíticas não é suficiente para chegar a bons sistemas de computador

- O modelo de engenharia de usabilidade
    + Pré-design
        * Conhecer o usuário: características indiviuais e tarefa
        * Análise Competitiva
        * Metas de Usabilidade
    + Design
        * Design inicial
            - Métodos participativos
            - Guidelines
            - Design coordenado
            - Padrões; identidade do produto
        * Desenvolvimento iterativo
            - Prototipagem
            - Teste
            - Design rationale
    + Pós-design
        * Feedback de estudo de campo

- Práticas de maior impácto na usabilidade do sistema:
    + Design iterativo, análise de tarefas
    + Teste empírico com usuários reais
    + Técnicas participativas (?)
    + Visita ao local de trabalho do usuário

- Benefícios
    + Economia de tempo
    + Economia financeira
    + Adoção de produtos adicionais

- Métodos Heurísticos
    + Procedimento
        * Características do sistema são comparadas com as guidelines heurísticas
        * Uma lista de incompatibilidades é coletada
    + Resultados
        * Detalhes onde design difere da guideline
        * Facilidade de aprendizado, consistência
        * Identificação de problemas menos graves

- Inspeção Heurística
    + **Passo 1**: Definir as heurísticas de usabilidade
        * As heurísticas são derivadas de princípios básicos de usabilidade
        * São realizadas adaptações a um produto específico
            - Guideline de design, pesquisa de mercado, documento de requisitos, análise de tarefas
    + **Passo 2**: Selecionar time de avaliação
        * Pesquisas empíricas mostram que de 3 a 5 avaliadores são suficientes para identificar 75% dos problemas de usabilidade de um sistema
    + **Passo 3**: Compilar material sobre o sistema
        * Análise de audiência
        * Especificação do sistema
        * Tarefas do usuário
        * Cenários de caso de uso
    + **Passo 4**: Inspeção pelos avaliadores
        * Inspeção individual de 1-2 horas, independente. Avaliadores devem procurar problemas de usabilidade que tanto um usuário novato quanto um mais experiente poderiam se deparar. No processo, devem realizar cada tarefa pelo menos duas vezes, tomando nota para cada problema encontrado
    + **Passo 5**: Feedback dos avaliadores
        * Compilação das notas tomadas durante a inspeção em um relatório estruturado de usabilidade contendo um sumário de todos os problemas de usabilidade encontrados, as heurísticas violadas por esses problemas e idéias de como corrigir esses problemas

- Graus de severidade usados na inspeção heurística
    + 4: "problema catastrófico - correção obrigatória antes de entregar o produto"
    + 3: "problema grave - alta prioridade na correção"
    + 2: "problema pequeno - baixa prioridade na correção"
    + 1: "problema cosmético - corrigir se tiver tempo"
    + 0: "não foi identificado problema de usabilidade"

- As 10 heurísticas de usabilidade de Nielson
    + H1 - Visibilidade do estado do sistema
        * Manter o usuário informado do que está ocorrendo
    + H2 - Consistência entre o sistema e o mundo real
        * Sistema deve falar a língua do usuário
        * Deve-se seguir convenções do mundo real
    + H3 - Controle do usuário
        * Usuários devem ter a opção de desfazer uma ação ou sair de um estado indesejado sem ter que passar por um processo extenso
    + H4 - Consistência de padrões
        * Usuários não devem ter que imaginar se diferentes palavras, situações ou ações significam a mesma coisa
    + H5 - Prevenção de erros
        * Design cuidadoso que previne a ocorrência de um problema
    + H6 - Reconhecimento em vez de lembrança
        * Tornar objetos, ações e opções visíveis. O usuário não deve ter que se lembrar de informações de uma parte do diálogo em outra.
        * Instruções de uso devem estar visíveis ou facilmente recuperáveis sempre que apropriado
    + H7 - Flexibilidade e eficiência de uso
        * Aceleradores podem aumentar a velocidade de interação de um usuário avançado de modo que o sistema possa atender a usuários experientes e iniciantes
    + H8 - Estética e design minimalista
        * Diálogos não devem conter informação que é irrelevante ou raramente necessária.
        * Toda unidade de informação extra em um diálogo compete com unidades de informação relevante e diminui sua visibilidade
    + H9 - Ajuda a reconhecer, diagnosticar e recuperar dados
        * Mensagens de erro devem ser expressa em linguagem plena e clara, indicando precisamente o problema e sugerir uma solução de maneira construtiva
    + H10 - Ajuda e documentação
        * Mesmo que seja desejável poder utilizar o sistema sem ter que recorrer à documentação, é necessário prover ajuda e documentação
        * A informação deve ser fácil de ser buscada, focada na tarefa do usuário, listando passos concretos e não ser muito extensa

- Outros métodos para inspeção de usabilidade
    + Avaliação heurística
    + Percurso Cognitivo
    + Inspeção formal de usabilidade
    + Percurso pluralístico
    + Inspeção de caracteríticas (_features_)
    + Inspeção de consistência
    + Inspeção de padrões

- Em síntese:
    + Métodos de inspeção de usabilidade avaliam aspéctos da usabilidade de um sistema sem fazer teste com o usuário
    + Avaliação heurística é um método rápido e efetivo em termos de custo para inspeção de usabilidade
    + Envolvem de 3 a 5 experts que avaliam o sustema seguindo um conjunto de heurísticas de usabilidade
    + Embora haja um conjunto geral de heurísticas, freqüêntemente precisam ser adaptadas a sistemas específicos
    + **A avaliação heurística não capta todos os aspectos de usabilidade!**

## Slide 5 - Fundamentos de Fatores Humanos em IHC 1
### O modelo de memória humana

- Os sistemas de memória humana
    + Sistemas sensoriais -> AIS -> MCD -> MLD

- Armazenamento de informação sensorial (AIS) 
    + A informação é salva como é recebida pelos orgãos sensoriais
    + Mantém uma imagem completa e acurada do mundo como recebida pelo sistema sensorial
    + Duração curta: 0.1s a 0.5s

- Memória de curta duração (MCD)
    + A infirmação retida não mais a imagem completa de eventos, mas a interpretação imediata deles
    + A informação pode ser mantida indefinidamente por repetição
    + Duração: décimos de segundo
    + Capacidade limitada: 5 +- 2 itens

- Memória de longa duração (MLD)
    + Não há limite prático para capacidade de MLD

- O Armazenamento de Informação
    + Há duas grandes régiões no cérebro: o hemisfério esquerdo e o direito (córtex), que diferem anatomicamente e possuem nomes diferentes
    + Mudanças estruturais e químicas devem ocorres no cérebro, como resultado da aquisição de novo conhecimento
        * MCD: ativação elétrica de um loop neural específico
        * MLD: estrutura permanente de circuitos neurais que acontece através de consolidação, que é a codificação química na estrutura de moléculas de proteína em cada sinápse, junto do crescimento de novas junções sinápticas

- Mantendo memória para uma entrada sensorial
    + Existem três tipos de resposta do sistema nervoso a um evento _X_:
        * Um sinal sensorial chegando inicia uma sequência de eventos elétricos que persiste indefinidamente. Isso gera uma reverberação que para somente com entradas estranhas ao loop, ocorrência de novos eventos, fadiga química nos neurônios ou eventos anormais
        * MCD ocorre quando há ativação elétrica seletiva de um loop neuronal específico

## Slide 6 - Fundamentos de Fatores Humanos em IHC 2
### O Modelo do Processador de Informação Humano (MPIH)

- Princípios do MPIH
    + **Princípio 1**: O tempo do ciclo no processador perceptual varia inversamente com a intensidade do estímulo
        * Lei de Bloch: \\(i \ast t = k, t < t_p \\)
    + **Princípio 2**: Princípio da especificidade da codificação
        * Operações de codificação específicas realizadas sobre o que é percebido determinam o que é armazenado, e o que é armazendo determina que pistas de recuperação são efetivas em prover acesso a essa informação
    + **Princípio 3**: Princípio da discriminação
        * A dificuldade da recuperação da memória é determinada pelos candidatos que existem na memória relativos às pistas para recuperação
    + **Princípio 4**: Princípio da variabilidade do ciclo do Processador Cognitivo
    + **Princípio 5**: Lei de Fitts
        * O tempo necessário para mover a mão para um alvo depende somente da precisão relativa requerida, isto é, a razão entre a distância ao alvo e seu tamanho
        * \\(T_{pos}=l_m log_2(2D/S)\\) onde \\(l_m = -(t_p + t_c + t_m)/log_2 e\\), onde _D_ é a distância entre a mão e o alvo, _S_ a largura do alvo e _e_ o erro
        * Em valores experimentais, _e_ = 0.07 e \\(l_m = 63\\)ms
    + **Princípio 6**: Lei da Prática
        * O tempo \\(T_n\\) necessário para realizar uma tarefa na n-ésima tentativa é dado por:
            - \\(T_n=T_1 n^{-a}\\), onde \\(a = 0.4\\)[0.2 ~ 0.6]
    + **Princípio 7**: Princípio da Incerteza (Lei de Hick)
        * O tempo T de tomada de decisão aumentada com a incerteza sobre o julgamento da decisão a ser feita e é dado por:
            - \\(T=I_c H\\), onde _H_ é a entropia de decisão e \\(I_c = 150\\)ms/bit
        * para n alternativas igualmente prováveis \\(H = log_2(n+1)\\)
        * Para alternativas com difernetes probabilidades \\(p_i\\) de ocorrência, \\(H = \sum_{i} p_i log_2 (1/p_i + 1)\\)
    + **Princípio 8**: Princípio da Racionalidade
        * Uma pesoa age de forma a alcançar suas metas através de ação racional, determinada pela estrutura de tarefa e suas entradas de informação e limitada pelo seu conhecimento e habilidade de processamento:
            - Metas + Tarefas + Operadores + Conhecimento + Limites de processamento -> Comportamento
    + **Princípio 9**: Princípio do Espaço do Problema
        * A atividade racional na qual as pessoas se engajam para resolver um problema pode ser descrita em termos de um conjunto de estados do conhecimento, operadores para mudar um estado para outro, restrições na aplicação desses operadores e conhecimento para decidir que operador aplicar em seguida
