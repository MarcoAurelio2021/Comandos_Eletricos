# Cálculos fundamentais em comandos elétricos

# Comandos Elétricos – Conceitos e Prática

Este guia reúne os **cálculos fundamentais** e os principais pontos do **dia a dia em comandos elétricos**.  

---

## 🔢 1. Cálculos Fundamentais

### a) Potência elétrica
- **Trifásico**  
  \[
  P = U \cdot I \cdot \cos\varphi \cdot \sqrt{3}
  \]

- **Monofásico / CC**  
  \[
  P = U \cdot I
  \]

---

### b) Corrente nominal de motores
\[
I = \frac{P}{\sqrt{3}\cdot U \cdot \eta \cdot \cos\varphi}
\]

- \(P\) = potência no eixo (W)  
- \(\eta\) = rendimento  
- \(\cos\varphi\) = fator de potência  

---

### c) Dimensionamento de proteção
- **Fusíveis / Disjuntores**: normalmente entre **1,25× a 1,5× Inominal**.  
- **Relé térmico**: ajustado para **100% da corrente nominal** da placa do motor.  

---

### d) Queda de tensão em cabos
\[
\Delta U = \frac{2 \cdot \rho \cdot L \cdot I}{A}
\]

- \(ρ\) = resistividade (cobre ≈ 0,0175 Ω·mm²/m)  
- \(L\) = comprimento (m)  
- \(A\) = seção do condutor (mm²)  

> Limite típico de queda de tensão: **3% a 5%**.  

---

### e) Velocidade síncrona
\[
n_{sync} = \frac{120 \cdot f}{p}
\]

- \(f\) = frequência da rede (Hz)  
- \(p\) = número de polos do motor  

---

### f) Escorregamento (slip)
\[
s = \frac{n_{sync} - n_{m}}{n_{sync}} \times 100\%
\]

- \(n_{sync}\) = rotação síncrona  
- \(n_{m}\) = rotação real do motor  

---

## 🛠️ 2. O que Acontece no Dia a Dia

### 🔹 Montagem de circuitos
- Botões **NA/NF**  
- **Contatores** para acionamento  
- **Relés térmicos** para proteção  
- Intertravamentos (elétricos e mecânicos)  

---

### 🔹 Partidas de motores
- **Partida direta (DOL)** – simples, mas corrente alta  
- **Estrela-triângulo** – reduz corrente de partida  
- **Soft-starter** – partida eletrônica controlada  
- **Inversor de frequência (VFD)** – controle de velocidade e torque  

---

### 🔹 Lógica de comando
- **Intertravamentos** – impedem dois contatores de fechar ao mesmo tempo  
- **Auto-manutenção (retenção)** – contator mantém-se ligado após soltar o botão  
- **Sinalização** – lâmpadas ou LEDs para status  

---

### 🔹 Manutenção
- Medição de **corrente, tensão, continuidade**  
- Teste de **bobinas de contatores**  
- Verificação de **fusíveis e relés térmicos**  
- Troca de **botoeiras e sensores (fim de curso)**  

---

### 🔹 Segurança
- **Lockout/Tagout** – bloqueio e etiquetagem  
- **EPI** – luvas, óculos, detector de tensão  
- **Normas NR10** – obrigatórias no Brasil  

---

## ✅ Resumindo
- Cálculos mais usados:  
  - **Corrente nominal**  
  - **Potência**  
  - **Queda de tensão**  
  - **Ajuste de proteção**  

- Rotina prática:  
  - Montagem de **painéis de comando**  
  - Partida e **reversão de motores**  
  - Dimensionamento de **contatores, relés e cabos**  
  - Diagnóstico de **falhas comuns**  

---

📌 Esse material pode servir como **guia rápido** para quem trabalha com comandos elétricos.  
