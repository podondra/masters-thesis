NAME = thesis

$(NAME).pdf: $(NAME).tex spec_sky_surveys.tex domain_adaptation.tex experiments.tex references.bib spectra_appendix.tex
	xelatex $(NAME)
	bibtex $(NAME)
	xelatex $(NAME)
	xelatex $(NAME)

slides: slides.tex references.bib
	xelatex slides
	biber slides
	xelatex slides
	xelatex slides

clean:
	$(RM) $(NAME).aux \
		$(NAME).bbl \
		$(NAME).blg \
		$(NAME).lof \
		$(NAME).log \
		$(NAME).lot \
		$(NAME).out \
		$(NAME).pdf \
		$(NAME).toc \
		domain_adaptation.aux \
		experiments.aux \
		spectra_appendix.aux \
		spec_sky_surveys.aux \
		slides.aux \
		slides.bbl \
		slides.bcf \
		slides.blg \
		slides.log \
		slides.nav \
		slides.out \
		slides.pdf \
		slides.run.xml \
		slides.snm \
		slides.toc 
