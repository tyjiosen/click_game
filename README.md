git submodule update --init


cd ./skynet

make linux


cd ./3rd/lua-cjson

make (install lua if necessary)

mv cjson.so ../../luaclib/cjson.so


./run.sh

now you can visit: http://0.0.0.0:521/index.html
