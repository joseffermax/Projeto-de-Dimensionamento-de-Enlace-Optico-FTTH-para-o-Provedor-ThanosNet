<h1 align="center">🔌 Projeto ThanosNet - Enlace Óptico 🌐</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Concluído-brightgreen.svg" alt="Status do Projeto">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="Licença MIT">
  </a>
</p>

<p align="center">
  Projeto de dimensionamento de enlace óptico FTTH para atendimento de até 100 clientes, 
  desenvolvido com uso do software <strong>UISP Design</strong> da Ubiquiti.
</p>

<p align="center">
  <strong>📡 Simulação realista com cálculo de perdas, divisão por splitters e validação técnica!</strong>
</p>

---

## 📝 Sobre o Projeto

O **ThanosNet - Enlace Óptico** é um projeto acadêmico desenvolvido na disciplina de **Comunicações Ópticas**, que tem como objetivo o planejamento e análise de um enlace óptico PON (Passive Optical Network) para atender 100 residências com conexão de 100 Mbps cada.

Utilizando o software profissional **UISP Design**, da Ubiquiti, foi modelada toda a topologia da rede, incluindo a divisão por portas da OLT, tipos de splitters, distâncias, perdas ópticas e validação com dados reais de potência.

---

## 🔍 Especificações Técnicas

- **OLT Utilizada**: UFiber OLT 4  
  - 4 portas | Até 512 clientes  
  - Potência de TX: 1.5 a 5 dBm  
  - Sensibilidade RX: -8 a -28 dBm  

- **ONU Utilizada**: UFiber NanoG  
  - Uma para cada cliente  
  - Potência TX: 0.5 a 5 dBm  
  - Sensibilidade RX: -8 a -28 dBm  

- **Distância Total do Enlace**: 497,24 metros  
- **Clientes Atendidos**: 100  
- **Velocidade Estimada por Cliente**: 100 Mbps  

---

## 🌐 Topologia e Divisão de Rede

- **Porta 1 (Azul)**: 25 clientes  
- **Porta 2 (Amarela)**: 25 clientes  
- **Porta 3 (Vermelha)**: 25 clientes  
- **Porta 4 (Rosa)**: 25 clientes  

---

## 🔧 Splitters Ópticos Utilizados

- UF-SPLITTER-4 (13 unidades) — perda: 7,4 dB  
- UF-SPLITTER-8 (1 unidade) — perda: 10,5 dB  
- UF-SPLITTER-32 (4 unidades) — perda: 17 dB  

---

## 📊 Cálculo de Potência

- **Potência de Saída da OLT**: 4 dBm  
- **Sensibilidade mínima da ONU**: -28 dBm  
- **Orçamento Óptico**: 32 dB  
- **Perdas Totais Consideradas**: 21,525 dB  
- **Margem de Potência Restante**: 10,475 dB  
- **Status**: Enlace viável e funcional 

---

## 💰 Orçamento Estimado

| Item                        | Quantidade | Preço (USD)   |
|-----------------------------|------------|---------------|
| UFiber OLT 4                | 1          | 1.189,00      |
| UFiber NanoG (ONU)          | 100        | 6.900,00      |
| Splitter UF-SPLITTER-32     | 4          | 172,00        |
| Splitter UF-SPLITTER-4      | 13         | 130,00        |
| Splitter UF-SPLITTER-8      | 1          | 13,00         |
| Cabo de Fibra (600m)        | —          | 200,00        |
| Conectores e acessórios     | —          | 100,00        |
| **Total Estimado**          | —          | **US$ 8.720,00** |

---

## 🗺️ Visualização da Rede

🔗 A topologia do projeto pode ser visualizada no software UISP Design da Ubiquiti por meio deste link:  
👉 [Ver Projeto no UISP Design](https://ispdesign.ui.com/#p=5032504141a94c8db7ad25ad89b1ae37)

---


## 📜 Licença

Distribuído sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## 👨‍🏫 Orientação

Projeto desenvolvido como parte da disciplina **Comunicações Ópticas**, sob orientação do professor:  
**Ewerton Rômulo Silva Castro**

---

## 📧 Contato 📫

- 📧 Email: [joseffermax1472@gmail.com](mailto:joseffermax1472@gmail.com)  
- 💼 LinkedIn: [Joseffer Maxwel](https://www.linkedin.com/in/joseffer-maxwel-4309ab243)  
- 🧠 Lattes: [Joseffer Maxwel Oliveira das Mercês](http://lattes.cnpq.br/2695955591585329)  
- 🏅 Credly: [Joseffer Maxwel Oliveira Das Merces](www.credly.com/users/joseffer-maxwel)

---

<h2 align="center">🚀 Conectando o futuro com redes ópticas eficientes e de alta performance! 🌐</h2>
