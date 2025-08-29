# Script-de-verificar-certificados<br>
Script de verificar certificados e tal, só jogar no site e puxar, cadastro é manual infelizmente<br>
Use no WordPress.<br>


1- Adicione o plugin Snippets no seu Wordpress. <br>
2- Clique em adicionar novo.<br>
3- Coloque o nome cert (ou o que vc quiser)<br>
4- Cole o código html em anexo no código<br>
5- adicone o banco de dados da seguinte maneira:<br>
<br>
  5a- la na linha 29 tem o exemplo:<br>
    {<br>
    name: 'João da silva',<br>
    certificates: [<br>
      { course: 'NOME DO CURSO', date: '01/01/2000', hours: '4 horas' }<br>
    ]<br>
  },<br>
  5b- Subistitua o nome do curso pelo nome do curso (óbivio), a data pela data do curso e as horas.<br>
<br>
6- Salva tudo e va até o fim da página vai ter o código mais ou menos assim:<br>
<br>
<img width="321" height="38" alt="image" src="https://github.com/user-attachments/assets/6c9668d7-66ba-4a6f-b42d-393c08daae03" />
<br>Copie<br>
<br>
7- no campo do backend editor do wordpress da página que vc quer que tenha a validalçao do certificado cola o código<br>
[code_snippet id=5 name="cert"]<br>
<br>
<img width="1427" height="354" alt="image" src="https://github.com/user-attachments/assets/d9b5cc39-4e42-4bfe-aa56-d737abdeb8d9" /><br>
<br>
fim

abraço
