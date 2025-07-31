# 🎯 Roblox Aimbot Advanced

Um sistema de aimbot avançado para Roblox com interface gráfica completa, sistema FOV e múltiplas funcionalidades de customização.

## ✨ Características

### 🎮 Funcionalidades Principais
- **Aimbot Automático**: Trava automaticamente no jogador mais próximo
- **Sistema FOV**: Campo de visão customizável com indicador visual
- **Interface Moderna**: GUI completa com design moderno e responsivo
- **Ajuste de Mira**: Personalização completa do offset da mira (X, Y, Z)
- **Detecção Inteligente**: Sistema que ignora teammates automaticamente

### 🔧 Controles
| Tecla | Função |
|-------|--------|
| `F` | Liga/Desliga o aimbot |
| `H` | Mostra/Oculta a interface |
| `X` | Desativa o aimbot rapidamente |
| `T` | Troca para o próximo alvo |
| `G` | Liga/Desliga o sistema FOV |
| `C` | Mostra/Oculta o círculo FOV |

### 🎨 Interface
- **Design Moderno**: Interface escura com elementos arredondados
- **Controles Intuitivos**: Botões grandes e fáceis de usar
- **Informações em Tempo Real**: Mostra alvo atual e distância
- **Configurações Avançadas**: Ajuste fino de todos os parâmetros

## 🚀 Como Usar

### Instalação
1. Copie o código do script
2. Execute em um executor de scripts Roblox (Synapse X, KRNL, etc.)
3. A interface aparecerá automaticamente no canto superior direito

### Configuração Básica
1. **Ativar Aimbot**: Clique no botão "🔴 DESATIVADO" ou pressione `F`
2. **Configurar FOV**: Ajuste o tamanho do campo de visão (padrão: 100)
3. **Ajustar Mira**: Modifique os valores X, Y, Z conforme necessário

### Configuração Avançada
- **Offset da Mira**: Ajuste fino para diferentes tipos de armas
- **Tamanho FOV**: Entre 10-500 pixels de raio
- **Distância Máxima**: 200 studs por padrão
- **Intervalo de Checagem**: 0.1 segundos para performance otimizada

## ⚙️ Configurações Detalhadas

### Sistema FOV
```lua
FOV_ENABLED = false        -- Liga/desliga o sistema FOV
FOV_SIZE = 100            -- Tamanho do círculo FOV (pixels)
FOV_CIRCLE_VISIBLE = true -- Visibilidade do círculo FOV
```

### Offset da Mira
```lua
AIM_OFFSET = Vector3.new(0, -0.5, 0)  -- Ajuste da posição da mira
```

### Outros Parâmetros
```lua
MAX_DISTANCE = 200           -- Distância máxima para detecção
TARGET_CHECK_INTERVAL = 0.1  -- Intervalo de checagem de alvos
```

## 🛡️ Recursos de Segurança

- **Detecção de Time**: Ignora automaticamente jogadores do mesmo time
- **Verificação de Vida**: Não mira em jogadores mortos
- **Validação de Distância**: Respeita o limite máximo configurado
- **Sistema FOV**: Evita travamento em alvos fora do campo de visão

## 🎯 Funcionalidades Técnicas

### Sistema de Detecção
- Busca inteligente por alvos válidos
- Priorização por proximidade ao centro da tela
- Fallback para proximidade por distância
- Verificação contínua de validade do alvo

### Performance
- Otimizado para 60+ FPS
- Checagem de alvos limitada por intervalo
- Renderização eficiente da interface
- Uso mínimo de recursos do sistema

### Compatibilidade
- ✅ Funciona na maioria dos jogos Roblox
- ✅ Compatível com diferentes tipos de arma
- ✅ Suporte a diferentes resoluções
- ✅ Interface responsiva

## 📋 Requisitos

- Executor de scripts Roblox funcional
- Roblox atualizado
- Jogos que suportem modificação de câmera

## ⚠️ Avisos Importantes

> **Disclaimer**: Este script é apenas para fins educacionais e de teste. O uso em jogos online pode resultar em banimento da conta. Use por sua própria conta e risco.

### Recomendações de Uso
- Teste apenas em servidores privados
- Não abuse das funcionalidades
- Respeite outros jogadores
- Use com moderação

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se livre para:
- Reportar bugs
- Sugerir melhorias
- Enviar pull requests
- Compartilhar feedback

## 📝 Changelog

### v1.0.0
- ✨ Lançamento inicial
- 🎯 Sistema de aimbot básico
- 🖥️ Interface gráfica completa
- 🎮 Controles por teclado
- 📊 Sistema FOV
- ⚙️ Configurações avançadas

## 📞 Suporte

Encontrou algum problema? Precisa de ajuda?
- Abra uma **Issue** neste repositório
- Descreva o problema detalhadamente
- Inclua informações sobre o executor usado

---

<div align="center">

**⭐ Se este projeto foi útil, deixe uma estrela!**

**🔧 Desenvolvido com foco em performance e usabilidade**

</div>
