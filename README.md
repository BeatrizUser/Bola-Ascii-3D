# BolaASCII Quicante - Three.js WebGL Effects

Este é um exemplo de aplicação web que utiliza a biblioteca Three.js para renderizar efeitos em WebGL. O efeito específico implementado neste código é a renderização de elementos em ASCII, no caso uma bola quicante.

## Como utilizar

1. Faça o download dos arquivos deste repositório ou clone-o para o seu ambiente local.

2. Abra o arquivo `index.html` em um navegador da web compatível.

3. O navegador irá renderizar a cena 3D com um objeto esférico animado e um plano. O objeto esférico será exibido usando caracteres ASCII.

4. Utilize o mouse para interagir com a cena. Você pode arrastar o mouse para girar a câmera e aplicar zoom in/out.

## Requisitos

- Navegador da web compatível com WebGL.
- Acesso à internet para carregar as dependências do Three.js.

## Dependências

Este código utiliza a biblioteca Three.js para renderização 3D e os seguintes módulos e efeitos:

- `three.module.js`: Biblioteca principal do Three.js.
- `AsciiEffect.js`: Efeito para renderização de elementos em ASCII.
- `TrackballControls.js`: Controle para interação do usuário com a cena.

As dependências são importadas utilizando a funcionalidade de import maps, que é um mecanismo de importação de módulos ainda em desenvolvimento. Certifique-se de ter acesso à internet para carregar essas dependências a partir dos URLs fornecidos no código.

## Personalização

Você pode personalizar a aparência da cena e do objeto esférico alterando as configurações dos materiais, luzes e geometria no código-fonte.

## Contribuição

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou adição de recursos a este projeto. Você pode abrir uma issue ou enviar um pull request.

## Créditos

Este exemplo foi baseado nos exemplos fornecidos na documentação oficial do Three.js (https://threejs.org).