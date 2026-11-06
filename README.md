# SIZE-scan
 # Smart Clothing Size 📐👾

**Uma mesma tecnologia, infinitas aplicações: da conveniência no e-commerce de moda até soluções que salvam vidas.**

O **Smart Clothing Size** é um projeto de Visão Computacional desenvolvido originalmente para a Feira de Ciências do SENAI. O objetivo principal do ecossistema é mapear o corpo do usuário em tempo real para extrair medidas físicas precisas e sugerir o tamanho ideal de roupas no e-commerce, reduzindo taxas de devolução e melhorando a experiência de compra.

A grande genialidade deste projeto é que a sua base técnica — o **Rastreamento Postural (Pose Tracking)** — serve como fundação para diversas outras verticais de mercado, desde a moda até a detecção de quedas na segurança em saúde.

---

## 🚀 Funcionalidades e Conceitos Base

*   📍 **Rastreamento de Pontos Corporais (Pose Tracking):** Mapeamento em tempo real de pontos-chave do corpo humano (como ombros, quadril e joelhos).
*   📐 **Análise Espacial e Geometria:** Processamento matemático e geométrico baseado em distâncias de píxeis e proporções para extrair medidas físicas reais do usuário.
*   🛠️ **Algoritmo Adaptável:** Uma prova prática de como dominar o ecossistema base do Python abre portas para transitar facilmente entre soluções de conveniência corporativa e sistemas de monitoramento crítico de saúde.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando as principais ferramentas do ecossistema de Inteligência Artificial e Ciência de Dados em Python:

*   **Python:** Linguagem base do projeto.
*   **MediaPipe:** Framework do Google utilizado para o rastreamento postural e detecção dos pontos-chave faciais e corporais (*pose estimation*).
*   **OpenCV:** Biblioteca líder para manipulação, processamento de imagem e renderização gráfica dos pontos na tela.

> *Nota de escalabilidade:* A arquitetura lógica base de análise geométrica deste projeto pode ser facilmente integrada com outros modelos de detecção, como o **YOLOv8/YOLOv11 (Pose)**, para ambientes que exijam maior robustez de tracking em condições adversas.

---

## 🎨 Como Funciona (Lógica de Engenharia)

1.  **Captura de Frame:** O sistema inicializa o fluxo de vídeo através da webcam ou câmera do dispositivo usando `OpenCV`.
2.  **Mapeamento de Esqueleto:** O framework `MediaPipe` processa a imagem do usuário e retorna as coordenadas tridimensionais (X, Y, Z) dos pontos anatômicos principais.
3.  **Cálculo Geométrico:** O algoritmo em Python isola os pontos de interesse (ex: distância entre ombros ou comprimento do tronco) e converte as distâncias relativas em medidas físicas estimadas.
4.  **Entrega do Output:** O software exibe visualmente o esqueleto mapeado na tela e sugere o tamanho ideal (PP, P, M, G, GG).

---

## 👥 Autores e Contexto

Projeto desenvolvido e apresentado orgulhosamente na **Feira de Ciências do SENAI**, validando conceitos práticos de Inteligência Artificial, Machine Learning e Engenharia de Software aplicados ao mundo real. Os authored do projeto foram todos alunos da rede de ensino SESI/SENAI: Júlia Victoria Gentil, Anne Caroline Amaral, Melyne Ferreira e João Rafael Serafim. 

