# CG_M1_Terreno Procedural

# Projeto de Ferramenta de Voxel em Unity

## Objetivo

Este projeto tem como objetivo demonstrar a habilidade de utilizar blocos (voxels) para construção de formas em espaço tridimensional. O sistema de voxel pode ser utilizado para diversas finalidades, como subdividir o mundo em partes menores, otimizar processamento gráfico e criar estruturas complexas.

A proposta é criar uma ferramenta que permita gerar, manipular e configurar estruturas voxel de maneira procedural, oferecendo ao usuário controle sobre as propriedades dos voxels (como tipo e cor).

## Instruções

- Realizado por Marcelle Andrade Pereira

## Requisitos do Projeto

- O projeto deve ser desenvolvido utilizando a **Unity**.
- Deve ser possível **gerar estruturas voxel** automaticamente.
- O usuário deve poder **apagar** a estrutura atual e iniciar uma nova.
- Deve permitir ao usuário escolher **diferentes tipos de voxel** e configurar suas cores, entre outras propriedades.

### Funcionalidades

- **Gerador Procedural de Terreno**: Criação de terrenos voxel de forma procedural, com ajustes dinâmicos de tamanho, altura e complexidade.

### Sugestões de Uso:

- **Gerador de Terreno Procedural**: Crie terrenos de forma automática com ruído Perlin para variações realistas.

## Tecnologias Utilizadas

- **Unity**: Para o desenvolvimento do ambiente 3D e interface do usuário.
- **C#**: Linguagem de programação utilizada para manipulação do terreno e geração procedural.

## Como Usar

1. **Clonando o Projeto**:
   ```
   git clone https://github.com/seu-repositorio/unity-voxel-generator.git
   ```

2. **Abrir o Projeto no Unity:** Após clonar o repositório, abra o projeto na versão recomendada da Unity (2020.3 ou superior).

3. **Executar o Projeto:** Basta pressionar o botão "Play" no Unity para começar a gerar e manipular o terreno com voxels.

## Controles Disponíveis 
- Sliders: Ajustam os parâmetros do terreno (tamanho X, Z, altura e entropia).
- Dropdowns: Permitem selecionar o tipo de voxel e o gradiente de cores.
- Botão de Reset: Restaura os valores padrões do terreno e reseta os voxels.

## Estrutura do Projeto
A organização do código segue o padrão MVC:

Controllers: Responsáveis pela lógica de controle e interação entre a interface e a geração procedural.
TerrainUIManager.cs: Gerencia a interface do usuário (UI) e interações.
Models: Lógica de geração e configuração do terreno voxel.
TerrainGenerator.cs: Gera o terreno voxel e aplica as configurações definidas pelo usuário.
Views: Interface de controle que permite ao usuário interagir e visualizar as mudanças no terreno.

## Entrega

### Projeto: 
- [Projeto Unity](https://github.com/Marcelleap/CG-Voxel/tree/main/Terreno%20Procedural)
  
### Imagem: 
<img src="https://github.com/Marcelleap/CG-Voxel/blob/main/Capturas/Captura%20I.png">
<img src="https://github.com/Marcelleap/CG-Voxel/blob/main/Capturas/Captura%20II.png">

### Videos: 
- [Código e Lógica](https://youtu.be/PGA0eP-mgzA)
- [Demostração](https://youtu.be/LiQNZuwDylc)

