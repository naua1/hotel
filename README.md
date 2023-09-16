
# hotel

##Senha que o codigo pede para ser executado 2678

linguagel usada: javascript
##
Atividade do Instituto Proa
# Hotel Management System
Este é um projeto de um sistema de gerenciamento de hotel desenvolvido com partes independentes e modularizado. O objetivo é criar uma plataforma para funcionários do hotel usarem, não para hóspedes.

Antes de começar, execute o código e observe o comportamento.

# Funcionalidades
# Autenticação
Ao acessar o sistema, solicita o nome do hotel e exibe "O nome do hotel é {Hotel}".
Pergunta o nome do usuário e uma senha. A senha deve ser "2678".
Exibe "Bem vindo ao Hotel {Hotel}, {Nome}. É um imenso prazer ter você por aqui!" após a autenticação.
Exibe "Muito obrigado e até logo, {Nome}" ao sair do sistema.
Gerenciamento de Quartos
Permite o usuário solicitar o valor de uma diária no hotel e a quantidade de dias de hospedagem.
Valida as informações para garantir que o valor da diária não seja negativo e que a quantidade de dias não seja negativa nem maior que 30.
Solicita o nome do hóspede.
Pergunta se o usuário confirma a reserva e exibe os detalhes.
Exibe uma mensagem de confirmação ou cancelamento da reserva.
# Cadastro de Hóspedes
Permite o usuário definir o valor padrão da diária.
Cadastra hóspedes com seus nomes e idades.
Hóspedes com menos de 6 anos têm gratuidade.
Hóspedes com mais de 60 anos pagam metade da diária.
Exibe a quantidade de gratuidades, meias hospedagens e o custo total considerando todos os hóspedes informados.
Cadastro e Pesquisa de Hóspedes
Permite o usuário cadastrar e pesquisar hóspedes.
Limite máximo de 15 cadastros.
Mostra se o hóspede foi encontrado ou não.
# Gerenciamento de Eventos
Calcula o custo total da contratação de garçons para um evento.
Pergunta se o usuário aceita os valores e exibe a mensagem de reserva efetuada ou não.
Buffet para Eventos
Calcula a quantidade de café, água e salgados para um evento com base no número de convidados.
Valida se a quantidade de convidados não excede 350.
Calcula o custo total do evento e pergunta se o usuário aceita os valores.
Escolha do Auditório
Indica qual dos dois auditórios (Laranja ou Colorado) é mais adequado com base no número de convidados.
Calcula a quantidade de cadeiras adicionais necessárias para o Auditório Laranja, se aplicável.
Pergunta se o usuário deseja fazer a reserva.
Reserva de Restaurante
Verifica se o restaurante do hotel está disponível com base no dia da semana e na hora informada.
Se disponível, solicita o nome da empresa e mostra a mensagem de reserva.
# Escolha de Combustível
Calcula qual combustível é mais econômico com base nos preços de álcool e gasolina em dois postos.
Aplica uma regra onde o álcool deve ser 30% mais barato que a gasolina para ser vantajoso.
Informa qual posto e combustível é mais econômico.
Orçamento de Manutenção de Ares Condicionados
Calcula o valor total do serviço de manutenção com base no valor por aparelho e na quantidade de aparelhos.
Aplica um desconto se a quantidade de aparelhos for maior que o mínimo para desconto.
Permite que o usuário informe várias empresas e exibe o menor valor orçado.
