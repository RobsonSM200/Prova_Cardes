# Prova_Cardes
Trabalho final de Engenharia de software

## 📘 Descrição do Projeto de Engenharia de Software.

Título: Construindo um Sistema de E-commerce com Design Top-Down e Funções

---
## 🎯 Objetivo

O projeto tem como finalidade desenvolver um sistema de e-commerce simplificado, aplicando conceitos de Design Top-Down e programação estruturada em funções/classes.
O sistema simula o fluxo completo de uma compra online — do cadastro do cliente à finalização do pedido — garantindo clareza nos requisitos e testes automatizados.

---
## 👥 Histórias de Usuário (HU)

#### O sistema foi modelado a partir de Histórias de Usuário que representam as necessidades do cliente:

HU-1: Cadastro do cliente para acessar a loja e acompanhar pedidos.

HU-2: Busca e seleção de produtos por nome e categoria.

HU-3: Visualização detalhada dos produtos (descrição, preço e imagens).

HU-4: Gerenciamento do carrinho (adicionar/remover itens e calcular total).

HU-5: Escolha da forma de pagamento (Pix, boleto, cartão).


---
## 🧪 Cenários de Utilização e Testes (Gherkin)


Cada HU foi detalhada com cenários de teste em Gherkin, permitindo que analistas validem o comportamento esperado:

Cadastro: Verificação de criação de conta com dados válidos.

Busca de produto: Pesquisa por nome e redirecionamento à página do item.

Página do produto: Exibição de informações completas do item.

Carrinho: Revisão dos itens adicionados e cálculo correto do subtotal/total.

Pagamento: Seleção da forma de pagamento e confirmação da compra.

---

## 📊 Diagrama (Visão Geral).

#### Fluxo simplificado do sistema:

Cliente → LojaRoupas → Estoque → Carrinho → Pagamento


Cliente: interage com o sistema via menu.

LojaRoupas: núcleo da aplicação, controla estoque e carrinho.

Estoque: lista de produtos disponíveis.

Carrinho: itens adicionados para compra.

Pagamento: etapa final, onde o pedido é confirmado.

---
## ✨ Resumo.

O projeto demonstra o ciclo completo de desenvolvimento de software:

levantamento de requisitos (HU)

definição de testes (Gherkin)

modelagem (Diagrama)

