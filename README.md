# CRM PAP – Plug Soluções

Sistema simples em **HTML + JS**, publicado via **GitHub Pages**, para controle de leads gerados pelas vendedoras no **PAP (porta a porta)**.

---

## 🚀 Como acessar
O sistema está publicado em:

```
https://leandroofonseca.github.io/crmplugsolucoes/
```

---

## 👩‍💼 Uso pelas vendedoras
Cada vendedora deve acessar o link com seu nome no final:

```
https://leandroofonseca.github.io/crmplugsolucoes/?vendedora=Carla
https://leandroofonseca.github.io/crmplugsolucoes/?vendedora=Bruna
https://leandroofonseca.github.io/crmplugsolucoes/?vendedora=Jéssica
```

O sistema mostrará automaticamente no topo: **Vendedora: Nome**.

---

## 📝 Campos do formulário
- **Data**
- **Nome da empresa**
- **Responsável pelo contato**
- **Telefone/WhatsApp**
- **Endereço**
- **Volume de impressões/mês**
- **Situação atual** (compra própria, já aluga, etc.)
- **Interesse identificado** (Frio, Morno, Quente)
- **Status do lead** (Novo, Em negociação, Proposta, Fechado, Perdido)
- **Observações**

---

## 📊 Funcionalidades
- Salva os leads do **dia atual** no próprio celular/computador (localStorage).
- Mostra **KPIs do dia** (quantos leads, propostas, fechados, taxa de conversão).
- Exporta **CSV**.
- Gera **relatório pronto para WhatsApp**:
  - Clica em **Copiar relatório WhatsApp**
  - Cola no grupo da Plug

---

## 🎨 Personalização
Parâmetros opcionais na URL:
- `&logo=URL` → para usar logo personalizada
- `&brand=%23HEX` → cor principal

Exemplo:
```
https://leandroofonseca.github.io/crmplugsolucoes/?vendedora=Carla&brand=%23001952&logo=https://seusite.com/logo.png
```

---

## ⚡ Observações
- Os dados **não são enviados para servidor**, ficam no dispositivo do usuário.
- Ao mudar de dia, inicia automaticamente uma nova agenda de leads.
- Botão **Zerar dia atual** apaga somente os leads daquele dia.

---

📌 Desenvolvido para a **Plug Soluções em Impressão** – simples, prático e direto para uso no PAP.
