build: clean 2048.yaml

2048.yaml: clean/2048.yaml
	kustomize build > $@

.PHONY: clean
clean:
	true
