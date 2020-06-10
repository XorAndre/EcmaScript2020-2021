# JavaScript 2020-2021
## Novas funcionalidades JavaScript
![Imagem JavaScript](https://miro.medium.com/max/3200/1*OF0xEMkWBv-69zvmNs6RDQ.gif); <br/>
O ECMAScript2020 , em sua próxima versão da especificação oficial subjacente ao JavaScript , deverá ser formalmente adotado em junho, sujeito à aprovação da ECMA International e do comitê técnico da ECMA que supervisiona a especificação. 
O ECMAScript 2020 apresenta vários recursos, desde um novo  import() recurso para carregar módulos até um novo BigInt tipo para trabalhar com números inteiros de precisão arbitrários. 

## Os recursos específicos planejados para o ECMAScript 2020 incluem:

- Um import()módulo “semelhante a uma função” carregando sintaxe para importar módulos de forma assíncrona com um especificador dinâmico. A proposta adiciona uma import(specifier)forma sintática, agindo de várias maneiras como uma função. Ele retorna uma promessa para o objeto de espaço para nome do módulo solicitado, criado após a busca, instanciação e avaliação das dependências de um módulo, junto com o próprio módulo. O  specifierserá interpretado da mesma maneira que em uma importdeclaração. Enquanto specifieré uma string, não é necessariamente uma literal de string; assim, código como import(`./language-packs/${navigator.language}.js`)funcionará. Isso não foi possível com as importdeclarações usuais . Com o plano,import() é proposto para trabalhar em módulos e scripts, fornecendo ao código de script um ponto de entrada assíncrono fácil no mundo do módulo e permitindo que ele comece a executar o código do módulo.
BigInt,um novo número primitivo para trabalhar com números inteiros de precisão arbitrários. BigIntpode representar números maiores que dois até a 53ª potência, o maior número que o JavaScript pode representar de maneira confiável com a primitiva Number. A BigInté criado anexando nao final do número inteiro ou chamando o construtor. <br>
- O matchAllmétodo para seqüências de caracteres, para produzir um iterador para todos os objetos correspondentes gerados por uma expressão regular global. A lógica por trás dessa proposta é que, se um desenvolvedor tiver uma string e uma expressão regular global ou pegajosa com vários grupos de captura, o desenvolvedor pode querer percorrer todas as correspondências, para as quais existem atualmente várias opções, mas com limitações. String#matchAll soluciona problemas fornecendo acesso a todos os grupos de captura e não alterando visivelmente o objeto de expressão regular em questão.
- allSettled, um novo combinador Promise que não provoca curto-circuito. Isso retorna uma promessa que é cumprida com uma variedade de instantâneos do estado da promessa, mas somente depois que as promessas originais são estabelecidas, ou seja, foram cumpridas ou rejeitadas.
- globalThis, fornecendo uma maneira universal de acessar o thisvalor global .
- Uma export * as ns from ‘module’sintaxe dedicada para usar em módulos.
- Padronização aumentada da for-inordem de enumeração , especificando parcialmente a ordem de enumeração em JavaScript.
import.meta,um objeto preenchido por host em Módulos que podem conter informações contextuais. Isso serve como uma metapropriedade JavaScript, mantendo metadados específicos do host sobre o módulo atual.
- Nullish coalescing , um operador de seleção de valor para lidar melhor com casos que envolvem acessos a propriedades. É um recurso de sintaxe para melhorar o trabalho com valores "nulos" ( nullou indefinidos).
Encadeamento opcional , um operador de acesso à propriedade e chamada de função que entrará em curto-circuito se o valor para acessar / chamar for nulo. 
 A última atualização do ECMAScript, ECMAScript 2019 , apresentava recursos como prototype.flatMap matrizes aninhadas.
