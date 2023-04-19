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
- O textarea se comporta de forma diferente de acordo com o dispositivo usado, de acordo com o protótipo. No desktop mantém seu tamanho fixo, adicionando uma barra de rolagem no conteúdo quando necessário. Em tablets e dispositivos móveis o textarea ajusta sua altura automaticamente pra caber o conteúdo adicional sem exibir barra de rolagem.
- Clicando na logo da aplicação é possível alternar os modos de criptografia "alura" e "cesar", permitindo que o usuario escolha entre usar o método de criptografia da alura ou o método de criptografia da <a href="https://pt.m.wikipedia.org/wiki/Cifra_de_C%C3%A9sar" target="_blank">cifra de césar</a>. 

Deploy: https://dantevicenzo.github.io/oracle-challenge-decodificador/

Apresentação em Vídeo: https://youtu.be/7rgGWMix8DE

Protótipo Figma: https://www.figma.com/file/tvFEYhVfZTjdJ5P24RGV21/Alura-Challenge---Desafio-1---L%C3%B3gica?node-id=0-1&t=rR60uE6zm5i8mpoq-0

## Screenshots

### Desktop

#### Modo Alura

<p float="left">
  <img src="https://user-images.githubusercontent.com/107062938/233083486-ade519e1-4105-489b-8ab8-424b02edf29c.png" align="top" width="30%" />
  <img src="https://user-images.githubusercontent.com/107062938/233083488-22ac2071-b69d-42d2-8ecf-f97f6a0d696b.png" align="top" width="30%" /> 
  <img src="https://user-images.githubusercontent.com/107062938/233083475-0b9d9eda-6098-4166-99f5-42a06a8d6c91.png" align="top" width="30%" />
</p>

#### Modo Cesar

<p float="left">
  <img src="https://user-images.githubusercontent.com/107062938/233086378-3787624d-bdc3-4d5d-8d50-88cddd2d7af0.png" align="top" width="30%" />
  <img src="https://user-images.githubusercontent.com/107062938/233086381-52855e00-754c-4e4e-a887-f13dcb11b7e1.png" align="top" width="30%" /> 
  <img src="https://user-images.githubusercontent.com/107062938/233086369-25535d42-b075-42ce-bf23-cf677878fe0b.png" align="top" width="30%" />
</p>

### Tablet

#### Modo Alura

<p float="left">
  <img src="https://user-images.githubusercontent.com/107062938/233087102-f2b59c42-b7d8-4f21-bbaa-a04e1c4f278a.png" align="top" width="30%" />
  <img src="https://user-images.githubusercontent.com/107062938/233087107-fc56d2fc-96d6-40eb-a515-f5caac2907cf.png" align="top" width="30%" /> 
  <img src="https://user-images.githubusercontent.com/107062938/233087109-7efe6c39-97fd-4008-837e-a2451c239374.png" align="top" width="30%" />
</p>

#### Modo Cesar

<p float="left">
  <img src="https://user-images.githubusercontent.com/107062938/233087371-f079ffbf-4352-4b94-9947-a7f14a828eb2.png" align="top" width="30%" />
  <img src="https://user-images.githubusercontent.com/107062938/233087374-e3aaa454-b227-404c-b334-4ffc0054366e.png" align="top" width="30%" /> 
  <img src="https://user-images.githubusercontent.com/107062938/233087361-0af82dc2-bb59-436f-915b-93499d1bc198.png" align="top" width="30%" />
</p>

### Smartphone

#### Modo Alura

<p float="left">
  <img src="https://user-images.githubusercontent.com/107062938/233087834-cf79f4d9-1649-4909-ba97-f2198864d6e9.png" align="top" width="30%" />
  <img src="https://user-images.githubusercontent.com/107062938/233087839-d554d521-ac38-451e-8af0-b562614b1a58.png" align="top" width="30%" /> 
  <img src="https://user-images.githubusercontent.com/107062938/233087833-bf496b2a-7a1c-42c8-b243-ee9a3e963204.png" align="top" width="30%" />
</p>

#### Modo Cesar

<p float="left">
  <img src="https://user-images.githubusercontent.com/107062938/233087885-91d566e3-8fdb-419f-a914-ca2d9ca55d2a.png" align="top" width="30%" />
  <img src="https://user-images.githubusercontent.com/107062938/233087892-27a4bc4e-35fb-46c0-a4b4-1ca4f5d00bba.png" align="top" width="30%" /> 
  <img src="https://user-images.githubusercontent.com/107062938/233087895-06c1bcba-ee86-459c-81d6-2b3d553e3bfd.png" align="top" width="30%" />
</p>

Badge de desafio concluído: ![Badge](https://d335luupugsy2.cloudfront.net/cms%2Ffiles%2F10224%2F1671211139Prancheta_3.png?utm_campaign=alura_latam_-_challenge_email_projeto_1_br&utm_medium=email&utm_source=RD+Station)
