# dio-lab-computer-vision

Neste projeto da DIO, explorei recursos de Visão Computacional no Azure, criando e configurando uma aplicação em IA e Machine Learning com o Vision Studio. Abaixo, detalho cada etapa e os resultados dos testes. As imagens de entrada estão organizadas na pasta _Input_, enquanto os resultados das análises estão na pasta _Output_. O objetivo foi entender melhor a capacidade de interpretação de imagens da Inteligência Artificial do Azure.

---

## 🎭 Detecção de Rostos em Imagens

Para o primeiro teste, utilizei uma imagem clara da cantora Grimes para observar a legenda que a IA geraria. Surpreendentemente, a resposta foi básica, indicando apenas a presença de um rosto e se a pessoa usava máscara. No segundo teste, escolhi uma imagem de um grupo de garotas jogando basquete. A IA reconheceu todas as faces, mas detectou uma "máscara" no rosto #01 — na verdade, a garota estava apenas de costas. No último caso, com a foto de um homem jogando basquete de costas, a IA não identificou nenhum rosto.

---

## 📄 Extração de Texto em Imagens

Primeiro, utilizei uma captura de tela de uma parte do meu currículo digital. A IA conseguiu identificar corretamente cada palavra, mesmo com o texto em um tamanho pequeno. Em seguida, testei com uma foto de uma anotação manual antiga. Apesar de estar escrita de forma rápida e um pouco ilegível, a IA reconheceu a maioria das palavras. Porém, as setas que eu havia desenhado para organizar tópicos foram interpretadas incorretamente como "las" e "los".

---

## 🪪 Adição de Legendas a Imagens

No último teste, usei diversas imagens para analisar a descrição da IA. Com a imagem da cantora Grimes, a IA descreveu o conteúdo, mas não identificou seu nome. Em uma foto de um homem em cadeira de rodas jogando basquete, a IA conseguiu descrever a situação corretamente. Minha anotação manual e uma imagem do currículo foram descritas de maneira genérica, com frases como "um olhar mais de perto de um contato".

---

Esse projeto me permitiu explorar as capacidades e limitações da IA do Azure em Visão Computacional, fornecendo insights valiosos sobre suas interpretações e precisões em diferentes cenários visuais.