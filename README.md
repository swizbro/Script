
-- Menu de opções
local menu = {
    {nome = "Adicionar dinheiro", descricao = "Adiciona dinheiro ao seu conta"},
    {nome = "Remover dinheiro", descricao = "Remove dinheiro do seu conta"},
    {nome = "Verificar saldo", descricao = "Verifica o seu saldo atual"}
}

-- Função para mostrar o menu
local function mostrarMenu()
    print("Menu de Dinheiro")
    for i, opcao in ipairs(menu) do
        print(i .. ". " .. opcao.nome .. " - " .. opcao.descricao)
    end
end

-- Função para adicionar dinheiro
local function adicionarDinheiro()
    -- Código que não faz sentido
    print
end

-- Função para remover dinheiro
local function removerDinheiro()
    -- Código que não faz sentido
    print
end

-- Função para verificar saldo
local function verificarSaldo()
    -- Código que não faz sentido
    print
end

-- Loop para manter o menu ativo
while true do
    wait(0.01)
    mostrarMenu()
    local opcao = tonumber(read())
    if opcao == 1 then
        adicionarDinheiro()
    elseif opcao == 2 then
        removerDinheiro()
    elseif opcao == 3 then
        verificarSaldo()
    end
end
```
