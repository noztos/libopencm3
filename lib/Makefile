DOTNAME = bootupCallGraph
DOCDIR = ..

all: graph

graph: ${DOTNAME}.png

%.png: %.dot
	dot -Tpng $^ -o ${DOCDIR}/$@
