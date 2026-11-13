# TiMe — Política de privacidade

**Última atualização:** 13 de novembro de 2026
**Vigência:** 13 de novembro de 2026

> Esta é uma tradução. Em caso de divergência, prevalece a versão em
> inglês ou turco.

---

## Em resumo

O TiMe é um app de acompanhamento do ciclo menstrual. Seus dados ficam
**armazenados no seu aparelho por padrão.** Não é preciso criar conta. Não
guardamos seus dados de ciclo em nossos servidores. Não compartilhamos
dados com redes de publicidade. O app não tem software de análise.

Seus dados só saem do aparelho nestas situações, e cada uma exige sua
escolha explícita:

1. **Comentários de IA e conversa** — quando você ativa o modelo online na conversa ou quando o modelo no aparelho não está
   disponível e você deu consentimento
2. **Troca com o Apple Saúde (HealthKit)** — quando você dá permissão
3. **Compras de assinatura**

Detalhes abaixo.

---

## 1. Controlador dos dados

| | |
|---|---|
| Nome | Batuhan Atabek |
| Endereço | Antalya, Turquia — solicitações podem ser enviadas por e-mail |
| E-mail | atabeksoft+privacy@gmail.com |

Esta política se aplica ao app TiMe para iOS.

---

## 2. Dados que tratamos

### 2.1 Dados que ficam no seu aparelho

Armazenados no banco de dados local do aparelho e **nunca enviados aos
nossos servidores:**

- Datas de início e fim da menstruação, duração dos ciclos
- Intensidade do fluxo
- Sintomas (físicos, humor, corrimento, pele, digestão, sono, energia)
- Registros de atividade sexual
- Temperatura basal, peso, resultados de testes de ovulação
- Suas notas de texto livre
- Preferências do app (idioma, unidades, horários de lembrete)
- Seu histórico de conversa com a IA

Parte desses dados é considerada **dado pessoal sensível** (dados de
saúde e sobre vida sexual) pela LGPD e pelo artigo 9 do RGPD. Por isso
nossa arquitetura padrão é o armazenamento no aparelho.

### 2.2 Dados que podem sair do seu aparelho

**a) Comentários de IA e conversa**

O TiMe usa primeiro **o próprio modelo de IA do seu aparelho** para gerar
comentários. Nesse caso, nenhum dado sai do aparelho.

Se você deu consentimento, também pode ativar "Conversa mais completa com o modelo online" em Ajustes. Ativada, suas mensagens da conversa vão primeiro para o modelo online seguindo as regras abaixo, mesmo que o aparelho suporte o modelo no dispositivo. Ela vem desativada e não afeta os comentários avulsos.

Se o aparelho não suportar esse modelo, você é consultada uma vez e
**somente com seu consentimento** o seguinte é enviado, por conexão
criptografada, a um servidor proxy e dali a um provedor de IA:

Enviado:
- A duração dos seus ciclos (só números)
- Sua fase atual do ciclo
- As etiquetas de sintomas que você escolheu
- As mensagens **que você digita** na conversa
- O idioma da interface

Não enviado:
- Seu nome, e-mail, data de nascimento
- Localização
- Identificador do aparelho ou de publicidade
- Datas exatas
- Notas de texto livre dos registros diários

Você pode retirar esse consentimento a qualquer momento em Ajustes. O app
volta então aos comentários baseados em regras e continua funcionando.

**Importante:** o texto que você digita na conversa é enviado ao provedor
exatamente como foi escrito. Recomendamos não digitar informações que
possam identificar você.

**b) Apple Saúde (HealthKit)**

Com sua permissão, fluxo menstrual, temperatura basal e registros
relacionados são trocados com o Apple Saúde. Esses dados ficam no seu
aparelho e não são enviados a nós.

**Não usamos dados do HealthKit para publicidade, marketing ou mineração
de dados, nem os compartilhamos com terceiros.**

**c) Assinaturas**

As compras são processadas pela Apple. **Não temos acesso aos seus dados
de pagamento.** Usamos o RevenueCat para acompanhar o status da
assinatura; apenas um identificador anônimo e o status da assinatura são
enviados, nunca seus dados de ciclo.

**d) Prevenção de abuso**

Para evitar abuso das solicitações de IA, um identificador aleatório
(UUID) é criado no aparelho. Ele não pode ser associado a você, serve só
para contar as solicitações diárias e é redefinido quando o app é
excluído.

### 2.3 Dados que não coletamos

- Nome, e-mail, telefone
- Localização
- Identificador de publicidade (IDFA)
- Contatos, fotos, câmera, microfone
- Análises de uso (o app não tem SDK de análise)

### 2.4 Recursos não oferecidos no momento

O app **não** oferece sincronização em nuvem (iCloud). Seus dados não são
sincronizados entre aparelhos. Se esse recurso for adicionado, esta
política será atualizada e seu consentimento será pedido separadamente.

---

## 3. Base legal

| Finalidade | Dados | Base legal |
|---|---|---|
| Previsão e acompanhamento do ciclo | Dados de ciclo e sintomas | Consentimento específico (LGPD art. 11, I; RGPD art. 9(2)(a)) |
| Comentários de IA (no aparelho) | Dados de ciclo e sintomas | Consentimento específico |
| Comentários de IA (online) | Dados do §2.2(a) | Consentimento específico separado |
| Integração com o Apple Saúde | Registros de saúde | Consentimento específico |
| Notificações | Datas previstas, horários escolhidos | Consentimento |
| Gestão da assinatura | ID anônimo, status da assinatura | Execução de contrato |
| Prevenção de abuso | Identificador aleatório do aparelho | Legítimo interesse |

---

## 4. Transferências internacionais

Se você consentir com comentários de IA online, os dados listados no
§2.2(a) são transferidos para servidores fora do seu país.

| Destinatário | Função | País |
|---|---|---|
| Cloudflare, Inc. | Servidor proxy | EUA |
| Google LLC | Provedor de IA — comentário avulso (Gemini) | EUA |
| Anthropic, PBC | Provedor de IA — conversa (Claude) | EUA |

Essa transferência se baseia no seu **consentimento específico.** Sem
consentimento, nenhum dado é transferido e o app continua funcionando no
aparelho.

Nosso proxy **não registra** seus dados de saúde.

Termos de dados dos provedores:
- Google: https://ai.google.dev/gemini-api/terms
- Anthropic: https://www.anthropic.com/legal/commercial-terms

---

## 5. Retenção

- **Dados no aparelho:** até você excluí-los. Excluir o app os exclui.
- **Dados enviados ao provedor de IA:** não são guardados por nós depois
  que a resposta é gerada.
- **Identificador antiabuso:** 24 horas.
- **Registros de assinatura:** conforme exigido por lei, mantidos pela
  Apple e pelo RevenueCat.

---

## 6. Seus direitos

Você tem direito de confirmação e acesso, correção, eliminação,
portabilidade, informação sobre compartilhamento, oposição e revogação do
consentimento a qualquer momento. Também pode apresentar reclamação à
autoridade de proteção de dados (no Brasil, a ANPD).

**Na prática:** como a maior parte dos seus dados fica só no seu
aparelho, você pode exercer vários desses direitos direto no app:

- **Acesso / portabilidade:** Ajustes → Exportar seus dados
- **Eliminação:** Ajustes → Excluir todos os dados
- **Revogar consentimento:** Ajustes → Consentimento de IA

Para outras solicitações: atabeksoft+privacy@gmail.com. Respondemos em até
30 dias.

---

## 7. Crianças

O TiMe não é direcionado a menores de 13 anos e não coletamos dados deles
intencionalmente. Se você é mãe, pai ou responsável e acredita que sua
criança usa o app, escreva para atabeksoft+privacy@gmail.com.

---

## 8. Segurança

- Os dados ficam no ambiente isolado padrão dos apps iOS.
- Bloqueio opcional do app (Face ID / Touch ID).
- Todo o tráfego de rede é criptografado com TLS.
- Nosso proxy não registra dados de saúde.
- Os dados enviados ao provedor de IA são minimizados.

Nenhum sistema é totalmente seguro. Recomendamos manter o aparelho
atualizado e usar um código de acesso.

---

## 9. Aviso médico

O TiMe serve para informação e acompanhamento pessoal. **Não é diagnóstico
médico, tratamento nem método contraceptivo.** As previsões são
estatísticas e podem errar. Consulte um profissional de saúde para
decisões sobre sua saúde.

---

## 10. Alterações

Se mudarmos esta política, mostraremos um aviso no app e atualizaremos a
data acima. Para mudanças relevantes, pediremos seu consentimento de
novo.

---

## 11. Contato

**Batuhan Atabek**
Antalya, Turquia — solicitações podem ser enviadas por e-mail
atabeksoft+privacy@gmail.com
