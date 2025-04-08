1 - Criar novo Repositório Local
![[Pasted image 20250408173102.png]]
2 - Nomear repositório e selecionar a Pasta Local
![[Pasted image 20250408173222.png]]
3 - Abrir o repositório como Workspace do Eclipse
![[Pasted image 20250408173318.png]]
4 - Selecionar a perspectiva Fluig Window>Open Perspective>Other>Fluig
![[Pasted image 20250408173353.png]]
5 - Criar o Projeto Fluig
![[Pasted image 20250408173616.png]]
6 - Mapear os Servidores na aba Servers  - Como cada repositório será um Workspace diferente do Eclipse, será necessário adicionar os servidores a cada novo repositório
![[Pasted image 20250408174046.png]]

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
![[Pasted image 20250408175254.png]]