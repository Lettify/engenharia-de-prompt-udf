# Tema: IA ajuda com código

### Primeira interação

#### Prompt: `Crie um exercício de Lua para praticar`
#### Resposta:
```
Ótima iniciativa! A melhor forma de aprender programação é colocando a mão na massa. Como Lua é uma linguagem muito famosa no desenvolvimento de jogos (como em Roblox, World of Warcraft, etc.), preparei um exercício com essa temática.

Aqui está um desafio focado no uso de **Tabelas (Tables)**, que são a estrutura de dados mais importante em Lua, além de funções e estruturas de repetição.

---

### O Desafio: Gerenciador de Inventário de RPG

Você foi encarregado de criar um sistema básico de inventário para um jogo de RPG. Seu objetivo é completar o código para que o jogador possa gerenciar os itens que carrega na mochila.

#### Requisitos:
Você precisará criar três funções:
1.  **`adicionarItem(nome, quantidade)`**: Deve adicionar a quantidade especificada do item ao inventário. Se o item já existir, apenas some a quantidade.
2.  **`removerItem(nome, quantidade)`**: Deve subtrair a quantidade do item. Se a quantidade chegar a zero (ou menos), o item deve ser removido completamente da tabela do inventário. Se o item não existir, exiba uma mensagem de erro.
3.  **`mostrarInventario()`**: Deve imprimir na tela todos os itens do inventário e suas respectivas quantidades. Se o inventário estiver vazio, deve avisar o jogador.

---

### Código Base

Copie o código abaixo para o seu editor ou testador de Lua online e preencha o interior das funções:

--- [CÓDIGO]
-- Tabela principal que guarda os itens
local inventario = {}

-- 1. Função para adicionar itens
function adicionarItem(nome, quantidade)
    -- Escreva seu código aqui
    
end

-- 2. Função para remover itens
function removerItem(nome, quantidade)
    -- Escreva seu código aqui
    
end

-- 3. Função para mostrar o inventário
function mostrarInventario()
    -- Escreva seu código aqui
    
end

-- ==========================================
-- TESTES: Não altere o código abaixo!
-- Se as suas funções estiverem corretas, 
-- a saída será igual à "Saída Esperada"
-- ==========================================

print("--- Adicionando Itens ---")
adicionarItem("Poção de Vida", 3)
adicionarItem("Espada Longa", 1)
adicionarItem("Poção de Vida", 2) -- Deve somar com as 3 anteriores
mostrarInventario()

print("\n--- Removendo Itens ---")
removerItem("Poção de Vida", 1) -- Deve sobrar 4
removerItem("Espada Longa", 1) -- Deve remover a espada completamente
removerItem("Escudo", 1) -- Deve dar erro, pois não existe
mostrarInventario()
--- [CÓDIGO]

---

### Saída Esperada

Se você programar tudo certinho, quando rodar o código, o terminal deverá imprimir exatamente isso:

> \--- Adicionando Itens ---
> Inventário:
> - Poção de Vida: 5
> - Espada Longa: 1
> 
> \--- Removendo Itens ---
> Erro: Você não possui Escudo no inventário.
> Inventário:
> - Poção de Vida: 4

*Dica: Para iterar sobre a tabela no `mostrarInventario`, lembre-se de usar o laço `for chave, valor in pairs(tabela) do`.*

---

Gostaria que eu conferisse o seu código quando terminar, ou prefere que eu já te mande o gabarito com a solução completa?
```

