## Perguntas (Git e GitHub - básico)
1. Qual a diferença entre `git init` e `git clone`?

R: git init -> iniciar o repositório local
git clone -> clonar um repositorio remoto do github.

2. O que faz o comando `git status`?

R: git status mostrar o status do repositório ( oque foi alterado, criado, excluído e etc )

3. Para que serve o `git add` antes do `git commit`?

R: git add -> comando que adiciona alteraçoes feitas na branch
git commit -> salvar oq foi feito na branch.

4. Qual a diferença entre `git pull` e `git fetch`?

R: git pull -> pega o repositório remoto e alinhar ele com o local ( Caso tenha feito algum commit, o repositorio local será atualizadoe ficara igual ao remoto ) 
git fetch -> baixar as referências  de um outro repositorio.

5. O que é um branch e por que ele é usado?

R: Uma branch é como se fosse uma copia do repositorio local ou remoto ( depende de onde voce vai fazer ela ), e é usado para fazer features,bugFix e etc

6. O que é um Pull Request no GitHub?

R: Um PR (Pull Reqest) é uma solicitaçao para juntar 2 branchs. 

7. Explique a diferença entre branch de origem e branch de destino em um PR.

R:  A branch de origem é sua branch principal, e a de destino é a secundaria por exemplo (a branch master esta em produçao e a develop é a branch de testes antes de mandar para a produçao)

8. O que acontece se duas pessoas alterarem a mesma linha de um arquivo em branches diferentes?

R: Quando elas forem juntar vai dar conflito (Odeio conflitos de branch)

9. Para que serve o arquivo `.gitignore`?

R: ignora certas pastas ou arquivos importantes, por ex o .env do qual pode carregar chaves de api e etc.

10. Qual é a função do `README.md` em um projeto?

R: Documentação de um projeto para outros desenvolvedores nao se perderem enquanto executam ele.