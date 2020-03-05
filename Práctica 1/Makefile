OUT = ../bin/Práctica\ 1

all:
	@printf "\033[1;32m%s\n" "PRÁCTICA 1"
	@printf "\033[1;33m-> \033[33mCreando directorio de salida\033[0m...\n"
	@mkdir -p $(OUT)
	@printf "\033[1;33m-> \033[34mCompilando\033[0m \"%s.pdf\"...\n" \
	        "Práctica 1"
	@xelatex Práctica\ 1.tex > /dev/null
	@xelatex Práctica\ 1.tex > /dev/null
	@printf "\033[1;33m-> \033[33mRelocalizando fichero de salida\033[0m...\n"
	@mv Práctica\ 1.pdf $(OUT)
