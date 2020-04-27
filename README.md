An example `.bash_aliases` function for using this skeleton project:

    function tweego() {
        mkdir -p path/to/webserver/public/$1
        cp -R path/to/projects/$1/public/. path/to/webserver/public/$1
        path/to/tweego/tweego -o path/to/webserver/public/$1/index.html -m path/to/projects/$1/modules/ path/to/projects/$1/src/*.twee
    }
    
