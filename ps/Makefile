all: pss01a pss01b pss02a pss02b

pss01a:
	pandoc -V documentclass:article -V geometry:margin=0.5in -V pagestyle:empty pss01a-data-as-vectors.md -o pss01a-data-as-vectors.pdf

pss01b:
	pandoc -V documentclass:article -V geometry:margin=0.5in -V pagestyle:empty pss01b-linear-classifier-inference.md -o pss01b-linear-classifier-inference.pdf

pss02a:
	pandoc -V documentclass:article -V geometry:margin=0.5in -V pagestyle:empty pss02a-least-squares.md -o pss02a-least-squares.pdf

pss02b:
	pandoc -V documentclass:article -V geometry:margin=0.5in -V pagestyle:empty pss02b-knn-classifier.md -o pss02b-knn-classifier.pdf

