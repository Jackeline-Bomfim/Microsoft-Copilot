# Explorando os Recursos de IA Generativa com Copilot

#### Sumário

* [Links úteis](#links-úteis)
* [O que é Copilot](#o-que-é-o-copilot)
* [Para que serve o Microsoft Copilot](#para-que-serve-o-microsoft-copilot)
* [Interagindo com a IA](#interagindo)
* [Um pouco sobre IA Generativa](#ia-generativa)

#### Links úteis

* [Copilot](https://aka.ms/ai900-bing-copilot)
* [Azure OpenAI](https://aka.ms/ai900-azure-opinai)
* [Filters](https://aka.ms/ai900-content-filters)
* [Pedindo dicas para a IA](#agora-vamos-pedir-umas-dicas)


### O que é Copilot?

Foi lançado no dia 07 de fevereiro de 2023, Microsoft Copilot é um assistente de chatbot. Uma solução inovadora de assistência interativa, impulsionada pela inteligência artificial. Tem como finalidade ajudar sesus usuários com as atividades do dia a dia, funciona como um assistente que se integra com diversos aplicativos da marca, como Edge, windows 11, etc.<br>
Desenvolvido em parceria com a OpenAi (dona do famoso ChatGPT), ele integra noções contextuais com informações da internet, dados profissionais com as atividades desenvolvidas no pc, com isso ofere aos usuários melhores suportes, com garantia, privacidade e segurança.

### Para que serve o Microsoft Copilot?

A ferramenta serve como um assistente integrado, alimentado por [IA generativa](#ia-generativa). Ele permite interações em linguagem natural e pode auxiliar em diversas tarefas, como:
* Realizar pesquisas online, encontrar informações importantes e criar resumos ou apresentações;
* Abrir aplicativos, procurar arquivos, enviar e-mails, definir lembretes e alterar configurações;
* Fazer chamadas, buscar voos, reservar hotéis ou restaurantes;
* Criar conteúdo criativo, como gráficos, imagens, texto ou código;
* Gerenciar operações de negócios, incluindo contabilidade, faturamento, estoque, marketing e atendimento ao cliente.

### Interagindo

Vamos acessar o [Microsoft Copilot ](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html) para ter acesso a documentação ou você pode entrar direto na plataforma e seguir por aqui. [LINK Copilot](https://copilot.microsoft.com).
* Acesse com seu login e senha, o mesmo utilizado no Azure.
* Pronto você terá acesso ao chat e pode interagir com a IA.

No vídeo abaixo eu solicito a IA a craição de um gato sorrindo com uma flor na mão:

[![draw cat](/img/chat%20screen.png)](/video/draw%20cat.mp4)

#### Editando

Ainda temos a opção de editar as imagens geradas.

* clique sobre a imagem
* você pode compartilhar, baixar ou customizar
* clique em customizar

![designer](/img/Designer.png)

#### Agora vamos pedir umas dicas.

No vídeo abaixo vamos observar minha interação com o chat pedindo dicas de filmes de uma determinada categoria.

[![chat](/img/chat%20screen.png)](/video/tip.mp4)

Veja como a IA tenta completar minhas frases sugerindo palavras no chat.

Agora é sua vez de tentar, crie uma conta, acesse o Microsoft Copilot ou para você que já usa Windows 11 ele fica no canto inferir direito.

## 

### IA Generativa

É uma técnica de aprendizagem de máquina baseada em algoritmos onde se consegue produzir um conteúdo novo apartir de um já existente.<br>
As IAs são *treinadas* com milhares de dados e assim criam padrões de construção de novos elementos (informações). Exemplo **ChatGPT**.

Vamos a um exemplo que é citado no Curso da [DIO](https://www.dio.me).

Quando você está digitando um e-mail e a IA vai sugerindo as próximas palavras.

### Mas como ela faz isso?

Ao inserir a frase ***"Eu ouvi um cachorro latir alto para um gato"***. A IA faz um processo que chamamos de **Tokenização**, ela irá guardar cada palavra em um "número" e essa frase irá gerar um algoritmo como demostrado abaixo:

Eu = 1<br>
ouvi = 2<br>
um = 3<br>
cachorro = 4<br>
latir = 5<br>
alto = 6<br>
para = 7<br>
gato = 8<br>

Gerando a sequência [123456738], isso é o que chamados de inserção ou incorporação.

* podemos observar que o "um" é registrado apenas uma vez e seu número se repete na sequência gerada.

