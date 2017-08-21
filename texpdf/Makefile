#Make para instalação e para tornar o comando padrão

all: getPrograms getSrcipt putScript

getPrograms:
	sudo apt-get install texlive texlive-latex-extra texlive-lang-portuguese

getSrcipt: texpdf
	chmod +x texpdf

putScript:
	sudo cp -a -u $(PWD)/texpdf /bin
