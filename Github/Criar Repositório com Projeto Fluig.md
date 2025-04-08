1 - Criar novo Repositório Local

![image](https://github.com/user-attachments/assets/5db4ec37-897a-438c-bb85-a46029ed8914)

2 - Nomear repositório e selecionar a Pasta Local

![image](https://github.com/user-attachments/assets/b290ceee-5dc8-4a1b-a01b-d63de8adbdd6)

3 - Abrir o repositório como Workspace do Eclipse

![image](https://github.com/user-attachments/assets/aa22e041-9527-4603-9a97-2c44c6dc729f)

4 - Selecionar a perspectiva Fluig Window>Open Perspective>Other>Fluig

![image](https://github.com/user-attachments/assets/66abbcb9-2cbf-4969-9e44-f1f34806c198)

5 - Criar o Projeto Fluig

![image](https://github.com/user-attachments/assets/1ccd884b-c2a4-4dbc-a88e-19270fc7c85d)

6 - Mapear os Servidores na aba Servers  - Como cada repositório será um Workspace diferente do Eclipse, será necessário adicionar os servidores a cada novo repositório

![image](https://github.com/user-attachments/assets/83a992c3-e6f3-48ae-8218-6c1288da5dd1)


7 - Incluir no gitignore o código abaixo para não incluir os arquivos no repositório.
```
/.metadata
com.totvs.tds.ecm.dataservers
*.cache
```
/.metadata - pastas desnecessárias para o repositório Formulário
com.totvs.tds.ecm.dataservers - Mapeamento dos Servers, contem o login e senha do usuário o que pode vazar informações
*.cache - são os dados do servidor

8 - Realizar o commit e Publicar o repositório no Github

![image](https://github.com/user-attachments/assets/915570f3-78c1-4fd5-95f0-647aedbe9cbd)
