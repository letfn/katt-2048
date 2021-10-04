build: clean main.yaml ../main.yaml

../main.yaml: main.yaml
	kustomize build >$@

main.yaml: clean/main.yaml
	kustomize build clean >$@

.PHONY: clean
clean:
	touch clean/main.yaml
