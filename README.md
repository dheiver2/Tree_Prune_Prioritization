# Priorização de Poda de Árvores

Este projeto tem como objetivo priorizar árvores para poda usando um sistema de IA. Ele inclui código para gerar imagens de árvores, treinar um modelo para analisar essas imagens e otimizar rotas de poda com base em prioridades.

## Uso

1. **Treinamento do Modelo**:
   - Utilize o método `treinar_modelo_analise_imagens` para treinar o modelo de análise de imagens com imagens de árvores rotuladas.

2. **Análise de Imagens**:
   - Utilize o método `analisar_imagem` para analisar imagens individuais de árvores e determinar se a poda é necessária.

3. **Otimização de Rotas de Poda**:
   - Utilize o método `otimizar_rota` para otimizar rotas de poda com base nas prioridades das árvores.

## Exemplo

```python
# Instanciar o sistema de IA
sistema = SistemaIA()

# Treinar o modelo
sistema.treinar_modelo_analise_imagens(dados_treinamento_imagens, labels)

# Analisar imagens de árvores e otimizar rotas de poda
for arvore in arvores:
    necessita_poda, probabilidade = sistema.analisar_imagem(arvore)
    sistema.mostrar_imagem_arvore(arvore, necessita_poda, probabilidade)

sistema.otimizar_rota(arvores, prioridades)
```

## Estrutura do Projeto

- `create_tree_image.py`: Contém código para gerar imagens de árvores.
- `sistema_IA.py`: Define a classe do sistema de IA com métodos para treinamento, análise e otimização.
- `README.md`: Este arquivo fornece uma visão geral do projeto.

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
```

