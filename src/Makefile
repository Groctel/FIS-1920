OUT = ../bin/

all: saludo practicas relocalizacion

saludo:
	@printf "\033[1;32m%s\n" "FIS - PRÁCTICAS"
	@printf "\033[1;33m-> \033[33mCreando directorio de salida\033[0m...\n"
	@mkdir -p $(OUT)

practicas:
	@printf "\033[1;33m-> \033[34mCompilando\033[0m \"%s.pdf\"...\n" \
	        "FIS - Práticas"
	@xelatex FIS\ -\ Prácticas.tex > /dev/null
	@xelatex FIS\ -\ Prácticas.tex > /dev/null

relocalizacion:
	@printf "\033[1;33m-> \033[33mRelocalizando fichero de salida\033[0m...\n"
	@mv FIS\ -\ Prácticas.pdf $(OUT)
