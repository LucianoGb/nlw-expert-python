# nlw-expert-python

trilha de python

Criado o ambiente virtual com a biblioteca virtualenv
Instalado a biblioteca pylint dentro do ambiente virtual e baixei o plugin no vscode também.

Pylint:
snake_case -> Funções, Variaveis, Métodos
PascalCase -> Classes(POO) 
docstring pra funções

'''
    Alguma documentação de função e modulo
'''

Comando para geração do pylintrc(arquivo de configuração do pylint)
pylint --generate-rcfile > .pylintrc
para desabilitar uma regra do pylint basta pegar o código do erro ex: C0116:missing-function-docstring
colocar no pylintrc em disable e deixa igual abaixo.

disable=
    C0116, #missing-function-docstring (o que importa é o C0116 o resto é apenas o comentário do que ele significa)

