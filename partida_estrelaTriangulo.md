A partida estrela-triângulo é um método usado para reduzir a corrente de partida em motores de indução trifásicos, principalmente em motores de média e grande potência (geralmente acima de 5 cv).

🔹 O problema que ela resolve

Quando um motor parte direto na rede (partida direta), a corrente de partida pode chegar a 6 a 8 vezes a corrente nominal.

Isso pode causar quedas de tensão na rede elétrica e esforço mecânico muito grande no motor.

🔹 Como funciona a ligação

O motor trifásico tem seus enrolamentos de estator que podem ser ligados em estrela (Y) ou triângulo (Δ):

Estrela (Y):

A tensão de fase (em cada bobina) é menor que a tensão da rede.

Cada bobina recebe Vlinha / √3.

Exemplo: rede 380 V → cada bobina recebe ~220 V.

Corrente de linha ≈ 1/3 da corrente de partida direta.

Motor parte com menos esforço → torque reduzido (~1/3 do nominal).

Triângulo (Δ):

Cada bobina recebe a tensão de linha inteira.

Exemplo: rede 380 V → cada bobina recebe 380 V.

O motor já entrega seu torque nominal.

🔹 Etapas da partida estrela-triângulo

Partida em estrela (Y):

O motor recebe tensão reduzida.

A corrente de partida cai bastante.

O torque também cai (bom quando a máquina parte em vazio ou carga leve).

Comutação para triângulo (Δ):

Após alguns segundos, quando o motor já está girando (80–90% da velocidade nominal), um comando troca a ligação para triângulo.

Agora o motor recebe tensão plena → fornece torque e potência nominais.

🔹 Onde usar e onde não usar

✅ Indicado para:

Motores que podem partir em vazio ou com carga leve (ventiladores, bombas centrífugas, compressores pequenos).

❌ Não indicado para:

Máquinas que precisam de torque alto logo na partida (prensas, britadores, compressores pesados). Nestes casos usa-se outros métodos: soft-starter, autotransformador, inversor de frequência.

👉 Resumindo:
A partida estrela-triângulo serve para reduzir corrente de partida ao ligar motores trifásicos, trocando de estrela para triângulo após o motor já ter ganho velocidade.

### Porque só funciona estrela triângulo quando a tensão de linha é 220V e o motor é 220/380, e caso a tensão de linha for 380V, não funciona estrela triângulo para um motor 220/380.

🔹 A base: tensão do motor

Um motor trifásico normalmente vem com duas tensões de placa, por exemplo:

220/380 V (ligação Δ/Y)

380/660 V (ligação Δ/Y)

👉 Isso quer dizer:

Na menor tensão, o motor é ligado em Δ (triângulo).

Na maior tensão, o motor é ligado em Y (estrela).

🔹 Como a partida estrela-triângulo aproveita isso

Na partida estrela-triângulo, a lógica é:

Primeiro liga-se em estrela (Y) → cada bobina recebe Vlinha / √3.

Depois troca para triângulo (Δ) → cada bobina passa a receber a tensão de linha inteira.

🔹 Caso 1 – Rede 220 V, motor 220/380 V

Em triângulo (Δ) → cada bobina recebe 220 V → perfeito, é a tensão nominal da bobina.

Em estrela (Y) → cada bobina recebe 220 / √3 ≈ 127 V → motor parte com tensão reduzida (corrente menor).

✅ Funciona normalmente → é o caso clássico de estrela-triângulo.

🔹 Caso 2 – Rede 380 V, motor 220/380 V

Em triângulo (Δ) → cada bobina receberia 380 V.

⚠️ Mas a bobina do motor foi projetada para 220 V, ou seja, queimaria.

Em estrela (Y) → cada bobina recebe 380 / √3 ≈ 220 V → até estaria correto, mas o motor não pode ir para triângulo depois, porque receberia sobretensão.

❌ Por isso não dá para usar estrela-triângulo nesse caso.

🔹 Regra prática

Para usar estrela-triângulo, a tensão de linha da rede precisa ser igual à tensão mais baixa da placa do motor (Δ).

Assim:

Motor 220/380 V → rede 220 V.

Motor 380/660 V → rede 380 V.

Se ligar na tensão maior da placa (380 no motor 220/380), estrela-triângulo não é possível, porque em Δ o motor não aguenta.

👉 Resumindo:
A partida estrela-triângulo só funciona quando a tensão da rede coincide com a tensão em Δ do motor.
Caso contrário, ao mudar para Δ, o motor receberá sobretensão e queimará.