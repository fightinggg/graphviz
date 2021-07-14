# graphviz
Graphviz docker version

# HOW TO USE
```sh
echo 'digraph { a -> b }' > input.dot
docker run -it --rm -v $PWD:$PWD -w $PWD fightinggg/graphviz dot input.dot -Tsvg > output.svg
```

# alias
```
alias dot='docker run -it --rm -v $PWD:$PWD -w $PWD fightinggg/graphviz dot'
```
