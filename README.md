COntainer com a ferramenta de analise de codigo da linguagem GO

golanci-lint = ferramenta que faz verificação do código 

docker run --rm -itv $(pwd):/app -w /app golangci/golangci-lint golangci-lint run controllers/ database/ models/ routes/


echo $? = mostra o estado do ultimo processo executado, 0 é igual sucesso


Pipeline é os passos que voce automatiza, o makefile é um exemplo de pipeline




 docker compose up -d postgres = só sobe o banco de dados

 


git switch -c build = o git switch muda de branch se passar o -c e um nome ele cria uma branch e ja muda para essa nova branch

git add ./github = addiciona as mudanças

git commit -m "" = faz o commit e a flag -m deixa um comentario

git push origin build = faz o push para o repositorio

