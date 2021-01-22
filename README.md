## Aplicando design patterns na prática com C# :computer:

Projeto desenvolvido durante a aula **Aplicando design patterns na prática com C#** pelo instrutor Victor Fructuoso. O presente projeto faz parte das atividades requisitadas no **Bootcamp Decola Dev 2021**, uma parceria da Digital Innovation One e da Avanade. :orange:

-----

:writing_hand: <u>Pontos importantes</u>¹:

1. O que são Design Patterns?

- São soluções reutilizáveis para problemas que ocorrem no contexto do design de software.
- Se tornaram populares depois de serem apresentados no livro "Design Patterns - Elements of Reusable Object-Oriented Software", mais conhecido como _Gang Of Four_ (1994).



2. Seu uso promove:

- **Produtividade**: seus modelos de resolução já foram utilizados e testados inúmeras vezes.
- **Manutenção**: são baseados em soluções de baixo acoplamento e padronização de soluções.
- **Termos universais**: por serem amplamente conhecidos, facilitam as discussões técnicas.



3. É preciso observar alguns pontos:

- Alguns padrões surgiram para solucionar limitações de linguagens de programação com menos recursos no que diz respeito à abstração. Funcionavam como “gambiarras” que proporcionaram à linguagem a possibilidade de fazer implementações que não eram possíveis nativamente.
- Padrões **não** são soluções prontas. Assim, é necessário ajustar o padrão ao contexto do projeto.
- Padrões **não** são "balas de prata". Nem todo padrão/técnica se encaixa em todos os cenários.



4. Os Princípios do **S.O.L.I.D**.

   **S** (SRP) <u>Princípio da Responsabilidade Única</u>: uma classe deve ter um, e somente um, motivo para mudar.

   **O** (OCP) <u>Princípio Aberto-Fechado</u>: capacidade de estender um comportamento de uma classe, sem modificá-lo.

   **L** (LSP) <u>Princípio da Substituição de Liskov</u>: as classes bases devem ser substituíveis por suas classes derivadas.

   **I** (ISP) <u>Princípio da Segregação da Interface</u>: muitas interfaces específicas são melhores do que uma interface única.

   **D** (DIP) <u>Princípio da Inversão da Dependência</u>: depende de uma abstração e não de uma implementação.

   

5. Problemas comuns em aplicações que **não** usam o S.O.L.I.D.

- Duplicidade de código.
- Código sem estrutura coesa.
- Dificuldade de manter/evoluir.
- Pequenos ajustes podem quebrar o código, inclusive em outras partes do sistema.
- Dificuldade para executar e criar testes unitários.
- Dificuldade de reaproveitar código para outras aplicações.



6. Principais benefícios

- Fácil manutenção.
- Fácil entendimento.
- Organização.
- Aberta a receber novas funcionalidades sem danos colaterais.
- Reaproveitamento de código.
- Fácil adaptação a mudanças no escopo do projeto.



7. Exemplos práticos (WebAPI REST .NETCore)

Link: https://github.com/fructuoso/DesignPatternSamples



[^1]: Breve fichamento do que foi apresentado durante a aula.

