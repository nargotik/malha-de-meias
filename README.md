# Malha de Meias

Converte o desenho de uma meia (PDF ou imagem) num padrão de jacquard para máquinas de meias:
largura em pontos (ex.: 100 para um cilindro de 200 agulhas), número máximo de cores, proporção do ponto,
separação do fundo e dos contornos, e exportação em BMP indexado (4 bits) pronto a importar no Photon.

Corre tudo no browser — os ficheiros nunca saem do computador.

**App:** https://nargotik.github.io/malha-de-meias/

- `index.html` — a aplicação (HTML + JavaScript, sem build)
- `vendor/` — [pdf.js](https://mozilla.github.io/pdf.js/) 3.11.174 (Apache-2.0) para ler PDFs
