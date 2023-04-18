PLANTUML = java -jar /usr/share/plantuml/plantuml.jar
FILE = E-SOH-C4-landscape-diagram.puml

plantuml:
	$(PLANTUML) -DRELATIVE_INCLUDE="." -tpng -o "" $(FILE)
	$(PLANTUML) -DRELATIVE_INCLUDE="." -tpdf -o "" $(FILE)

clean:
	rm -f E-SOH-C4*png
	rm -f E-SOH-C4*pdf

