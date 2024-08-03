## Git e github mulheres em dados

### Instalando o Git

### Criando uma conta no GitHub

### Versionamento: Versionamento de software é um processo de controle de versões, definido através de “numerações” de históricos diferente. O Git controla esse histórico de versões de um mesmo código atribuindo uma numeração referente ao estado daquele código em determinado momento que foi salvo por uma pessoa específica.

### Repositório: É a pasta onde armazenamos o nosso projeto, dentro de um repositórios os projetos podem se dividir em módulos e outras divisões especificas para cada tipo de projeto. Todo repositório tem um arquivo.git, este arquivo indica que este repositório é rastreável para o Git. Ex: https://github.com/WoMakersCode/git-e-github

#### Readme> arquivo de descrição do repositório

### Commit: toda vez que você desejar salvar/registrar as alterações no seu projeto, você comita essas alterações. Um commit tem as alterações que são realizadas nela e uma mensagem descritiva, além de informações sobre o autor, a data, etc.

#### Chanche (Diff) O Git mantém o controle de versão rastreando as alterações e diferenças entre as versões dos arquivos “cadastrados” nele. O que o git entende por alteração de um arquivo? 1 – Criação, renomeação ou exclusão de arquivos. 2 – Inserção ou exclusão de uma linha em um arquivo ( uma linha modificada é uma inserção e uma exclusão)

### Branch: Branchs são separações de código, com elas, é possível que varias pessoas que atuem em um mesmo projeto independentemente. A Branch inicial de todo projeto é a Branch master, nas empresas geralmente criamos branchs de acordo com o ambiente que esse código será disponibilizado:

#### Develop: ambiente para uso em tempo de desenvolvimento. Depois de testar o que desenvolvemos em nossa máquina (ambiente local), o código é disponibilizado nesse ambiente.

#### Homolog: Após as alterações serem validades em ambiente de desenvolvimento, o código vai para a Branch/ambiente de homologação, onde pessoas de negócio podem validar a solução e pessoas da área de qualidade efetuam mais testes para validar a solução.

##### Master: Como dito anteriormente, é a Branch principal do nosso projeto, geralmente os códigos contidos nela são os que vão para produção, Produção é o site que é disponibilizado para o público. A equipe de desenvolvimento cria novas branchs para separar e desenvolver novas soluções para um produto de forma simultânea, bem como melhorar funcionalidades já existentes, trabalhando de forma paralela e independente,

### Merge: O merge consiste em unir duas branchs. Geralmente realizamos o merge para juntar alterações de dias branchs em que dias pessoas estavam atuando simultaneamente.

### Clone: Podemos transferir o repositório que está no github para nossa máquina local através de um clone. Dessa forma você terá acesso ao seu repositório localmente, podendo realizar as alterações e enviá-las para o github quando desejar.

### Pull: “Como eu continuo atualizada com o meu repositório remoto:” Com o comando git Pull podemos atualizar o nosso repositório local. É realizado um merge entre o repositório online (github) com o que temos localmente, dessa forma evitamos conflitos, estaremos com o conteúdo atualizado e poderemos enviar nossas futuras alterações.

### Push: “Como eu envoi as alterações que comitei localmente para a minha origem remota?” Com o comando git push podemos enviar nossas alterações locais para o nosso repositório remoto. Com o comando git push podemos enviar nossas alterações locais para o nosso repositório remoto. Dessa forma o repositório remoto estará atualizado com a sua versão local, e outras pessoas que forem acessar ele poderá ter uma versão mais atualizada.

### Fork: “Como eu posso contribuir com o repositório de outras pessoas? O Fork é bem semelhante ao cliente, porém ele só ocorre na interface gráfica do github. O repositório não será baixado para seu computador, mas você terá uma cópia dele na sua conta do github. Depois de ‘forkar’ um repositório de outra pessoa, você pode fazer pull-request para contribuir com o conteúdo no repositório principal.

### Pull Request: “Como posso enviar uma contribuição para o repositório de outra pessoa?” Fazendo um pull request. Após ‘forkar’ o repositório de outra pessoa, podemos resolver issues dele e fazer pull request enviando soluções para erros e adicionando novos conteúdos. A pessoa dona do repositório irá avaliar a sua pull request e se tiver, ok, será mergeada no repositório principal.
