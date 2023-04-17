# Decodificador de Texto - Oracle Next Education
Boas vindas ao primeiro desafio!<br/>

As "chaves" de criptografia que utilizaremos são:<br/>
A letra "e" é convertida para "enter"<br/>
A letra "i" é convertida para "imes"<br/>
A letra "a" é convertida para "ai"<br/>
A letra "o" é convertida para "ober"<br/>
A letra "u" é convertida para "ufat"<br/>

Requisitos:<br/>
- Deve funcionar apenas com letras minúsculas<br/>
- Não devem ser utilizados letras com acentos nem caracteres especiais<br/>
- Deve ser possível converter uma palavra para a versão criptografada e também retornar uma palavra criptografada para a versão original.<br/>

Por exemplo:<br/>
"gato" => "gaitober"<br/>
gaitober" => "gato"<br/>

A página deve ter campos para inserção do texto a ser criptografado ou descriptografado, e a pessoa usuária deve poder escolher entre as duas opções
O resultado deve ser exibido na tela.<br/>

Extras:<br/>
- Um botão que copie o texto criptografado/descriptografado para a área de transferência - ou seja, que tenha a mesma funcionalidade do ctrl+C ou da opção "copiar" do menu dos aplicativos.<br/>

Funcionalidades adicionais que eu desenvolvi pra agregar ao projeto:<br/>
- Validação automática do texto digitado no textarea para permitir apenas letras minúsculas e espaçamentos. Acentuações, caracteres especiais e números, não serão aceitas mesmo que o usuário tente inserir esses caracteres, garantindo a funcionalidade da aplicação, evitando bugs e mensagens de erro pro usuário final. Pra melhorar a experiência, caracteres com acentuação e em letra maiúsculas são substituídos por caracteres válidos ao invés de serem removidos. Ex: ã -> a, A -> a, Á -> a. Se não houver substituição válida o caractere é removido da textarea.
- Ao descriptografar, verificar se existe uma mensagem criptografada no texto, caso não tenha mensagem criptografada, exibir mensagem informando que nenhuma mensagem foi encontrada, caso tenha mensagem criptografada, seguir o fluxo normal da descriptografia.
- Animações nos botões para melhorar a experiência do usuário.
- Mensagem de feedback informando que o texto foi copiado para área de transferência, dentro da aplicação ou em uma modal.
- Design responsivo em qualquer dimensão
- Mensagem de feedback depois de copiar o texto
- Animações pra melhorar a experiência de usuário
- O texto de placeholder da textarea muda de acordo com o dispositivo usado, de acordo com o protótipo. Em desktop: "Digite seu texto aqui". Em tablets e celulares: "Digite seu texto".
- O textarea se comporta de forma diferente de acordo com o dispositivo usado, de acordo com o protótipo. No desktop mantém seu tamanho fixo, adicionando uma barra de rolagem no conteúdo quando necessário. Em tablets e dispositivos móveis o textarea ajusta sua altura automaticamente pra caber o conteúdo adicional sem exibir barra de rolagem.
- Clicando na logo da aplicação é possível alternar os modos de criptografia "alura" e "cesar", permitindo que o usuario escolha entre usar o método de criptografia da alura ou o método de criptografia da <a href="https://pt.m.wikipedia.org/wiki/Cifra_de_C%C3%A9sar" target="_blank">cifra de césar</a>. 

Protótipo figma disponibilizado pela oracle: https://www.figma.com/file/tvFEYhVfZTjdJ5P24RGV21/Alura-Challenge---Desafio-1---L%C3%B3gica?node-id=0-1&t=rR60uE6zm5i8mpoq-0

![Imagem de Exemplo](https://user-images.githubusercontent.com/91544872/157673876-2c51fc09-5bed-48c0-aad3-97fc7fa64d1d.png)

Badge de desafio concluído: ![Badge](https://d335luupugsy2.cloudfront.net/cms%2Ffiles%2F10224%2F1671211139Prancheta_3.png?utm_campaign=alura_latam_-_challenge_email_projeto_1_br&utm_medium=email&utm_source=RD+Station)
