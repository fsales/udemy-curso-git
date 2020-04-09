## udemy-curso-git
Git e Github para iniciantes

#### Dicas GIT
  
  - git diff -> verifica a diferença dos arquivos.

  - git checkout {nome_arquivo} volta para a versão após a alteração.

  - git reset head {nome_arquivo} -> retira o arquivo da stage.

  - git commit -am "mensagem" - adiciona todos arquivos modificados mais a mensagem.

  - voltar modificação git reset:

    - --soft: voltar o commit mais deixa o arquivo na stage pronto para ser comitado novamente.
	
      ```git reset -soft {hash do commit anterio ao que se quer voltar}```
    
    - --mixed: voltar o commit e remove o arquivo da stage deixando as modificações realizadas.
    
      ```git reset -mixed {hash do commit anterio ao que se quer voltar}```
    
    - --hard: voltar o commit e apaga tudo que foi feito
    
      ```git reset -hard {hash do commit anterio ao que se quer voltar}```


### Git Hub
   - Gerar chave [ssh] (https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

    - Inicializando repositório local com o remoto
	 		- testar conexão SSH 
      ```sh
        $ ssh -T git@github.com
      ```
			
			- adicionar repositório remoto	 		
      ```sh
			  $	git remote add origin git@github.com:fsales/udemy-curso-git.git
      ```

			- verificar endereço remote
      ```sh
				$ git remote -v
      ```

		  - commit
      ```sh
				$ git push -u origin master
      ```
      

