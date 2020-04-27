An example `.bash_aliases` function for using this skeleton project:

```function tweego() {
    mkdir -p ~phil/twine/public/$1
    cp -R ~phil/twine/projects/$1/public/. ~/twine/public/$1
    path/to/tweego/tweego -o path/to/webserver/public/$1/index.html -m path/to/projects/$1/modules/ path/to/projects/$1/src/*.twee
}```
