all: crime_analysis.owl

# This requires https://github.com/owlcollab/owltools
%.owl: %.omn
	owltools --catalog-xml catalog-v001.xml $< -o $@
