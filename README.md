COntainer com a ferramenta de analise de codigo da linguagem GO

golanci-lint = ferramenta que faz verificação do código 

docker run --rm -itv $(pwd):/app -w /app golangci/golangci-lint golangci-lint run controllers/ database/ models/ routes/


echo $? = mostra o estado do ultimo processo executado, 0 é igual sucesso


Pipeline é os passos que voce automatiza, o makefile é um exemplo de pipeline




 docker compose up -d postgres = só sobe o banco de dados

 


