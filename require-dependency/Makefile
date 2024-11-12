MVN=mvn -T 1C --batch-mode -s .settings.xml -P codeartifact -U -nsu

.PHONY: compile
compile:
	$(MVN) package -Dmaven.test.skip.exec=true

.PHONY: cleancache
cleancache:
	rm -rf ~/.m2/repository
