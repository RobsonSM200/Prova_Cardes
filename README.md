# Prova_Cardes
Trabalho final de Engenharia de software
## 
📘 Descrição do Projeto de Engenharia de Software
Título: Construindo um Sistema de E-commerce com Design Top-Down e Funções
🎯 Objetivo
O projeto tem como finalidade desenvolver um sistema de e-commerce simplificado, aplicando conceitos de Design Top-Down e programação estruturada em funções/classes. A ideia é simular o fluxo completo de uma compra online, desde o cadastro do cliente até a finalização do pedido, garantindo clareza nos requisitos e testes automatizados.
👥 Histórias de Usuário
O sistema foi modelado a partir de Histórias de Usuário (HU), que representam as necessidades do cliente:
HU-1: Cadastro do cliente para acessar a loja e acompanhar pedidos.
HU-2: Busca e seleção de produtos por nome e categoria.
HU-3: Visualização detalhada dos produtos (descrição, preço e imagens).
HU-4: Gerenciamento do carrinho (adicionar/remover itens e calcular total).
HU-5: Escolha da forma de pagamento (Pix, boleto, cartão).
🧪 Cenários de Utilização e Testes (Gherkin)
Cada HU foi detalhada com cenários de teste em Gherkin, permitindo que analistas de qualidade validem o comportamento esperado:
Cadastro: Verificação de criação de conta com dados válidos.
Busca de produto: Pesquisa por nome e redirecionamento à página do item.
Página do produto: Exibição de informações completas do item.
Carrinho: Revisão dos itens adicionados e cálculo correto do subtotal/total.
Pagamento: Seleção da forma de pagamento e confirmação da compra.
💻 Implementação em Python
O sistema foi implementado em Python, utilizando classes e funções para organizar o código:
Classe Roupa: representa os produtos, com atributos como nome, tamanho, preço e estoque.
Classe LojaRoupas: gerencia o estoque, carrinho e fluxo de compra.
Funções principais: listar estoque, adicionar ao carrinho, visualizar carrinho e finalizar compra.
Interface simples via menu interativo no terminal, permitindo ao usuário navegar pelas opções.
📊 Diagrama (Visão Geral)
O diagrama do sistema pode ser representado como:
Cliente → LojaRoupas → Estoque → Carrinho → Pagamento
Cliente: interage com o sistema via menu.
LojaRoupas: núcleo da aplicação, controla estoque e carrinho.
Estoque: lista de produtos disponíveis.
Carrinho: itens escolhidos pelo cliente.
Pagamento: etapa final, onde o pedido é confirmado.
✨ Em resumo, o projeto demonstra o ciclo completo de desenvolvimento de software: levantamento de requisitos (HU), definição de testes (Gherkin), implementação (Python) e modelagem (Diagrama). É um ótimo exemplo de aplicação prática dos conceitos de Engenharia de Software em um sistema realista de e-commerce.
Quer que eu prepare também um diagrama UML (em texto ou imagem) para ilustrar melhor as relações entre as classes e funções? Isso deixaria sua documentação ainda mais profissional.
