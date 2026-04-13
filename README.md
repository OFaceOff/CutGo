# 🎬 CutGo — Extrator de Frames de Vídeo

Ferramenta profissional para extração de frames de vídeos.
Rápido, seguro e privado, tudo acontece diretamente no seu navegador, sem envio para servidores.

---

## 🚀 Sobre o projeto

O **CutGo** é uma aplicação web que permite extrair imagens (frames) de vídeos diretamente no navegador, sem necessidade de upload para servidores.

Ideal para:

* Criadores de conteúdo
* Designers
* Desenvolvedores
* Qualquer pessoa que precise capturar frames de vídeos rapidamente

---

## ⚡ Funcionalidades

* 📁 Upload de vídeos (MP4, WebM, MOV)
* 🎬 Preview completo do vídeo
* 🎚️ Controle de intervalo de captura
* 🎯 Limite máximo de frames configurável
* ✂️ Extração parcial (intervalo de tempo)
* 📊 Barra de progresso em tempo real
* ⏱️ Estimativa de tempo de processamento
* 🖼️ Galeria responsiva com preview
* ⬇️ Download individual de frames
* 📦 Download em lote (ZIP)
* 🛑 Cancelamento de processamento
* 🎨 Interface moderna (dark mode)
* 📱 Responsivo (mobile friendly)

---

## 🔒 Privacidade

* ✅ 100% processamento local
* ❌ Nenhum upload de arquivos
* ❌ Nenhuma comunicação com servidores
* 🔐 Seus vídeos nunca saem do seu dispositivo

---

## 🧠 Como funciona

O CutGo utiliza tecnologias nativas do navegador:

* `<video>` para reprodução
* `<canvas>` para captura de frames
* `toBlob()` para geração eficiente de imagens
* `JSZip` para compactação

Todo o processamento acontece no cliente (client-side).

---

## 🛠️ Tecnologias utilizadas

* HTML5
* CSS3 (Flexbox + Grid)
* JavaScript (Vanilla)
* JSZip (via CDN)

---

## 📦 Como usar

1. Acesse o site
2. Faça upload de um vídeo
3. Ajuste:

   * Intervalo de captura
   * Limite de frames
   * Qualidade da imagem
4. Clique em **"Extrair Frames"**
5. Baixe:

   * Imagens individuais
   * Ou todas em ZIP

---

## ⚙️ Instalação local

```bash
# Clone o repositório
git clone https://github.com/OFaceOff/CutGo.git

# Entre na pasta
cd cutgo

# Abra o arquivo
index.html
```

---

## 🌐 Deploy

Este projeto é totalmente frontend e pode ser hospedado facilmente em:

* GitHub Pages
* Vercel
* Netlify

---

## ⚠️ Limitações

* Vídeos muito longos podem consumir muita memória
* A performance depende do navegador e do hardware
* Recomendado:

  * Limitar até ~200 frames
  * Usar intervalos maiores em vídeos longos

---

## 💡 Melhorias futuras

* Web Workers para processamento paralelo
* WebCodecs API (mais performance)
* Exportação em GIF
* Timeline interativa
* Preview em tempo real no scrub

---

## 🤝 Contribuição

Contribuições são bem-vindas!

1. Fork o projeto
2. Crie uma branch
3. Commit suas mudanças
4. Abra um Pull Request

---

## 📄 Licença

Este projeto está sob a [Licença](./LICENSE) definida no repositório.

---

## ⭐ Apoie o projeto

Se você achou útil, considere dar uma ⭐ no repositório!
