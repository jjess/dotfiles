# GOOSE RPI (Research/Plan/Implement) Pattern

https://goose-docs.ai/docs/tutorials/rpi

```
mkdir -p ~/.config/goose/recipes/subrecipes

curl -sL https://raw.githubusercontent.com/aaif-goose/goose/main/documentation/src/pages/recipes/data/recipes/rpi-research.yaml -o ~/.config/goose/recipes/rpi-research.yaml
curl -sL https://raw.githubusercontent.com/aaif-goose/goose/main/documentation/src/pages/recipes/data/recipes/rpi-plan.yaml -o ~/.config/goose/recipes/rpi-plan.yaml
curl -sL https://raw.githubusercontent.com/aaif-goose/goose/main/documentation/src/pages/recipes/data/recipes/rpi-implement.yaml -o ~/.config/goose/recipes/rpi-implement.yaml
curl -sL https://raw.githubusercontent.com/aaif-goose/goose/main/documentation/src/pages/recipes/data/recipes/rpi-iterate.yaml -o ~/.config/goose/recipes/rpi-iterate.yaml

curl -sL https://raw.githubusercontent.com/aaif-goose/goose/main/documentation/src/pages/recipes/data/recipes/subrecipes/rpi-codebase-locator.yaml -o ~/.config/goose/recipes/subrecipes/rpi-codebase-locator.yaml
curl -sL https://raw.githubusercontent.com/aaif-goose/goose/main/documentation/src/pages/recipes/data/recipes/subrecipes/rpi-codebase-analyzer.yaml -o ~/.config/goose/recipes/subrecipes/rpi-codebase-analyzer.yaml
curl -sL https://raw.githubusercontent.com/aaif-goose/goose/main/documentation/src/pages/recipes/data/recipes/subrecipes/rpi-pattern-finder.yaml -o ~/.config/goose/recipes/subrecipes/rpi-pattern-finder.yaml
```

Y leer el tutorial para entender cómo usarlo


# GOOSE superpowers

https://github.com/bdklahn/goose-superpowers

goose plugin install https://github.com/bdklahn/goose-superpowers

Habilitar el uso de superpowers en cada sesión de goose. Añadir a .bashrc:

```
# goose superpowers
# https://github.com/bdklahn/goose-superpowers
export GOOSE_MOIM_MESSAGE_FILE="~/.agents/plugins/goose-superpowers/MOIM.md"
```

source ~/.bashrc

goose session


