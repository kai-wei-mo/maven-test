MVN=mvn -T 1C --batch-mode -s .settings.xml -P codeartifact

.PHONY: compile
compile:
	$(MVN) package -Dmaven.test.skip.exec=true
