# Script-de-verificar-certificados
Script de verificar certificados e tal, só jogar no site e puxar, cadastro é manual infelizmente
Use no WordPress.


1- Adicione o plugin Snippets no seu Wordpress. 
2- Clique em adicionar novo.
3- Coloque o nome cert (ou o que vc quiser)
4- Cole o código html em anexo no código
5- adicone o banco de dados da seguinte maneira:

  5a- la na linha 29 tem o exemplo:
    {
    name: 'João da silva',
    certificates: [
      { course: 'NOME DO CURSO', date: '01/01/2000', hours: '4 horas' }
    ]
  },
  5b- Subistitua o nome do curso pelo nome do curso (óbivio), a data pela data do curso e as horas.

6- Salva tudo e va até o fim da página vai ter o código mais ou menos assim:

<img width="321" height="38" alt="image" src="https://github.com/user-attachments/assets/6c9668d7-66ba-4a6f-b42d-393c08daae03" />
Copie

7- no campo do backend editor do wordpress da página que vc quer que tenha a validalçao do certificado cola o código
[code_snippet id=5 name="cert"]

<img width="1427" height="354" alt="image" src="https://github.com/user-attachments/assets/d9b5cc39-4e42-4bfe-aa56-d737abdeb8d9" />

fim

abraço
