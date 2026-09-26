# Padrão de personagens — corpo inteiro | Projeto Conectando o Brasil

**Status:** padrão visual aprovado em 26/09/2026, para aplicar às fotos de referência que serão enviadas.  
**Uso:** gerar uma imagem individual por personagem; reutilizar como referência de identidade nas cenas do curta e no Google Flow.  
**Documento-base:** [docs/ESTRUTURA_PROJETO.md](../../docs/ESTRUTURA_PROJETO.md). Se houver revisão, manter coerência com o documento-base e registrar a nova versão aqui.

## Prompt principal

> Transforme **a pessoa da foto de referência** em um personagem 3D de longa-metragem de animação, com estética cinematográfica premium inspirada em filmes da DreamWorks. O resultado precisa ser **claramente animado e estilizado**, nunca uma fotografia retocada ou um humano renderizado de modo realista.
>
> **Identidade:** preserve a semelhança reconhecível com a pessoa original: formato do rosto, idade aparente, tom de pele, cabelo e penteado, olhos, sobrancelhas, barba, óculos e demais traços ou acessórios distintivos quando presentes. Não troque a identidade, não rejuvenesça, não embeleze exageradamente. Use olhos moderadamente maiores e expressivos, íris definidas, traços faciais suavemente simplificados, pele de animação lisa sem textura fotográfica, cabelo modelado em volumes estilizados e proporções adultas elegantes. Evite caricatura excessiva.
>
> **Enquadramento obrigatório:** mostrar **corpo inteiro, da cabeça aos sapatos**, com mãos e pés completos e visíveis, anatomia correta, cinco dedos em cada mão, postura natural e confiante. Uma pessoa por imagem, centralizada, com margem livre ao redor da silhueta. Manter proporções consistentes entre os personagens da equipe, sem cortar cabeça, mãos ou calçados.
>
> **Figurino obrigatório:** roupa social corporativa elegante nas **cores roxas da Vivo**, com harmonização em branco quando necessário: blazer ou paletó roxo, camisa social/blusa social, calça social ou saia social apropriada à pessoa, calçados sociais. A roupa pode variar discretamente entre personagens para conservar personalidade e função, mas deve pertencer à mesma equipe visual. Aplicar **a marca Vivo pequena e legível** no lado esquerdo do peito, como bordado ou aplicação de qualidade. Se uma arte oficial do logotipo for fornecida, usá-la fielmente; caso o gerador distorça as letras ou o símbolo, deixar uma área limpa para aplicar a marca oficial na finalização.
>
> **Direção de arte:** acabamento de filme 3D de animação, formas esculpidas, materiais de tecido estilizados, iluminação cinematográfica quente e suave com acentos roxos, expressão acolhedora e profissional. Fundo neutro claro ou ambiente corporativo muito discreto; contraste suficiente para distinguir os contornos do traje roxo. Referência de personagem pronta para reutilização nas cenas do projeto. Preservar a mesma aparência facial, paleta, roupa e detalhes entre imagens futuras da mesma pessoa.
>
> **Restrições:** sem fotorrealismo, sem textura realista de pele, sem aspecto de foto filtrada, sem olhos desproporcionais, sem mudança de etnia ou idade, sem membros ou dedos extras, sem texto aleatório, sem logotipo inventado, sem corte do corpo.

## Uso por personagem

1. Anexar a foto de referência da pessoa e, quando disponível, o arquivo oficial do logo Vivo.
2. Substituir apenas o identificador `[PERSONAGEM / FRENTE]` no pedido: **“Aplique o padrão deste documento à pessoa anexada. Personagem: [PERSONAGEM / FRENTE]. Gere uma imagem individual de corpo inteiro.”**
3. Para a equipe, manter o mesmo grau de estilização, iluminação, escala visual e figurino roxo. As frentes são Comercial, Pós-vendas, Regionais e Centralizado; não atribuir nomes ou funções a uma pessoa sem confirmação na referência.
4. Conferir antes de aprovar: semelhança, visual de animação evidente, corpo inteiro, mãos e sapatos visíveis, roupa social roxa e marca Vivo correta.
5. Em cenas de mistério que mostrem personagens apenas do pescoço para baixo, manter o figurino e a identidade de corpo inteiro como referência interna de continuidade.

## Recuperação da continuidade

Se houver perda de contexto, mudança indevida do rosto, figurino ou estilo, ou se o usuário disser **STOP**, consultar este arquivo e o documento-base antes de retomar. A versão salva no repositório prevalece sobre lembranças da conversa.
