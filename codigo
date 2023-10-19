import random

# Dicionário de respostas do chatbot
respostas = {
    "olá": "Olá! Como posso ajudar?",
    "como você está?": "Eu sou apenas um programa de computador, então não tenho sentimentos, mas estou aqui para ajudar!",
    "adeus": "Até mais! Se precisar de alguma coisa, é só perguntar.",
    "o que é o curso de Sistemas de Informação?": "O curso de Sistemas de Informação é uma área que combina tecnologia da informação e negócios para resolver problemas usando sistemas de software. É uma área muito interessante!"
}


def responder(mensagem):
    mensagem = mensagem.lower()
    resposta = respostas.get(mensagem, "Desculpe, não entendi. Pode reformular a pergunta?")
    return resposta


# Função principal do chatbot
def chatbot():
    print("Olá! Eu sou um chatbot. Você pode me fazer perguntas ou dizer olá.")

    while True:
        mensagem = input("Você: ")
        if mensagem.lower() == "sair":
            print("Chat encerrado.")
            break
        else:
            resposta = responder(mensagem)
            print("Chatbot: " + resposta)


if __name__ == "__main__":
    chatbot()
