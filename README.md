# Projeto---Programa-multiplica-o-de-dois-n-meros
Programa

primeiro_n_C3_BAmero = None
segundo_n_C3_BAmero = None
resultado = None

def text_prompt(msg):
  try:
    return raw_input(msg)
  except NameError:
    return input(msg)


primeiro_n_C3_BAmero = float(text_prompt('Qual o primeiro número? '))
segundo_n_C3_BAmero = float(text_prompt('Qual o segundo número? '))
resultado = primeiro_n_C3_BAmero * segundo_n_C3_BAmero
print('O resultado da multiplicação é: ' + str(resultado))
