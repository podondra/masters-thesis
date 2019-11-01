NAME = thesis

$(NAME).pdf: $(NAME).tex spec_sky_surveys.tex domain_adaptation.tex experiments.tex references.bib
	xelatex $(NAME)
	bibtex $(NAME)
	xelatex $(NAME)
	xelatex $(NAME)

clean:
	$(RM) $(NAME).aux \
		$(NAME).bbl \
		$(NAME).blg \
		$(NAME).log \
		$(NAME).out \
		$(NAME).pdf \
		$(NAME).toc
