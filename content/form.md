# Formulário

A tag `<form>` é usada para criar um formulário HTML para entrada do usuário. Neste exemplo temos algumas da muitas tags utilizadas para desenvolver formulários em HTML.

```html
<form action="">
<fieldset>
    <legend>Conta:</legend>
	  <label for="email">Email:</label>
		<input type="email" id="email" name="email"><br>
		<label for="pwd">Senha:</label>
		<input type="password" id="pwd" name="pwd"><br><br>
</fieldset>

<fieldset>
    <legend>Pessoal:</legend>
		<label for="fname">Nome:</label>
		<input type="text" id="fname" name="fname"><br>
		<label for="phone">Telefone:</label>
	  <input type="tel" id="phone" name="phone" pattern="[0-9]{2}-[0-9]{4}-[0-9]{4}"><br>

		<label for="fname">Sexo:</label>
		<input type="radio" name="sex" id="female"><label for="female">Female</label>
		<input type="radio" name="sex" id="male"><label for="male">Male</label><br>

		<label for="birthday">Data de Nascimento:</label>
		<input type="date" id="birthday" name="birthday"><br>
		<label for="myfile">Foto de Perfil:</label>
		<input type="file" id="myfile" name="myfile"><br><br>
	</fieldset>
	
<fieldset>
    <legend>Endereço:</legend>
		<label for="street">Rua:</label>
		<input type="text" id="street" name="street"><br>
		<label for="number">Número:</label>
		<input type="number" id="number" name="number" min="1" max="5"><br>
		<label for="complement">Complemento:</label>
		<input type="text" id="complement" name="complement"><br>
		<label for="city">City:</label>
		<input type="text" id="city" name="city"><br>
		<label for="state">Estado:</label>
        <select name="state" id="state">
				<optgroup label="Região Sudeste">
          <option value="saopaulo">São Paulo</option>
          <option value="rio">Rio de Janeiro</option>
          <option value="minas">Minas Gerais</option>
          <option value="espiritosanto">Espirito Santo</option>
				</optgroup>
        </select><br><br>
		</fieldset>

<fieldset>
    <legend>Mensagem:</legend>
				<label for="mensage"><b>Deixe sua mensagem:</b></label><br>
        <textarea id="mensage" name="mensage" rows="4" cols="50"></textarea><br><br>
  <input type="checkbox" id="offer" name="offer" value="offer">
  <label for="offer">Aceito receber ofertas por email</label><br>
</fieldset><br>
	  <input type="submit" value="Submit">
</form>
```

**Exemplo Explicado:**

A tag `fieldset` cria conjuntos de campos agrupados dentro de uma linha container que vai identificar cada uma das sessões. E a tag `legend` cria uma legenda para cada `fieldset`, um texto que fica sobre as linhas.

A tag `input` serve para criar a grande maioria dos campos de formulários em HTML5 e a tag `label` para criar palavras relacionadas aos campos do formulário. Por padrão, na tag `input` colocamos os atributos `name=””` para definir um nome ao objeto e `id=””` para nome do campo e este dever ser único. O `for`atributo da `<label>`tag deve ser igual ao `id`atributo do `<input>`  para ligá-los.

**Tipos de Input e outros atributos**

* `type="text”` define um campo de texto. `size=””` para definir tamanho do campo, `maxlength=””` para definir a quantidade de caracteres.
* `type="password”` define um campo de senha.
* `type="email”` define um campo de e-mail.
* `type="tel”` define um campo de telefone. `pattern=”` atributo especifica uma expressão regular.
* `type="radio”` define um botão de rádio. Permitem que um usuário selecione APENAS UMA de um número limitado de opções.
* `type="date”` define um campo de data.
* `type="file”` define um campo de seleção de arquivo e um botão "Procurar" para uploads de arquivos.
* `type="number”` define um campo de números. `min=””` para definir o número mínimo e `max=””` para número máximo apresentado.
* `type=”submit”` define um botão para enviar os dados do formulário para um manipulador de formulários que geralmente é um arquivo no servidor com um script para processar dados de entrada.
* `type="checkbox"`define uma caixa de seleção. As caixas de seleção permitem que um usuário selecione ZERO ou MAIS opções de um número limitado de opções.

A tag `select` é usada para criar uma lista suspensa. A tag `option` define uma opção em uma lista de seleção e `optgroup` é usada para agrupar opções relacionadas.

A tag `textarea` define um controle de entrada de texto de várias linhas. O tamanho de uma área de texto é especificado pelos atributos `cols=""`e `rows=""`.

[Voltar a Home](../README.md)

