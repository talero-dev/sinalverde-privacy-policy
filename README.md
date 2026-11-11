# Privacy Policy — Sinal Verde: Simulado Detran

> The Brazilian Portuguese version of this policy is the primary text.
> This English version is a faithful translation of it; if the two ever diverge, the
> Portuguese version prevails.

**Application:** Sinal Verde: Simulado Detran
**Google Play identifier:** `com.talero.sinalverde`
**Data controller:** Talero
**Contact:** talero.dev@gmail.com
**Public address of this policy:** https://github.com/talero-dev/sinalverde-privacy-policy

---

## In short

- Sinal Verde **asks for no sign-up, creates no account and never asks for your name,
  tax number, email or phone number.**
- **We collect no personal data from you.** Your answers, your mock exams and your
  progress stay **on your device only**.
- The app **works entirely offline**. The internet is used only to show ads, fetch
  remote configuration and send usage statistics and crash reports — none of which is
  needed in order to study.
- The app **shows ads** (Google AdMob). Google's advertising and measurement tools
  collect data of their own, described in detail below.
- You can **review or withdraw your consent** at any time and **erase everything** via
  **Settings → Delete my data**.

---

## 1. Who we are and what this policy covers

This policy explains how the **Sinal Verde: Simulado Detran** application handles
data. It applies to the Android application distributed on Google Play under the
identifier `com.talero.sinalverde` and to no other service.

Sinal Verde is an **independent study application**. It has **no affiliation** with
Senatran, with the Ministério dos Transportes, with any state DETRAN or with any other
public body. It does not issue, query or modify official documents.

> **Note about the content in this version:** the question bank bundled in this
> version is a **non-official development sample**, and the application itself
> displays a warning saying so. That is a content matter rather than a privacy
> matter.

## 2. What we collect: nothing

We, Talero, **do not collect, receive or store any personal data about
you**. There is no server of ours: Sinal Verde has no backend of its own.

The application has **no accounts and no login**. We neither ask for nor have access
to:

- your name, email, phone number, tax ID, driving licence number or any document;
- your calendar, contacts, photos, files, camera or microphone;
- your precise (GPS) location.

### 2.1 What is stored on your device

So that the app can work, the following is written **locally**, into Room databases
and DataStore preferences inside the application's private storage:

| What | Why |
|---|---|
| Question bank, topics and road signs | Study offline |
| Answers given, right and wrong | Build the mistakes notebook and the statistics |
| Mock exams taken, scores and times | Show your history and your readiness score |
| Spaced-repetition cards and favourites | Organise your revision |
| Preferences (theme, text size, language, read-aloud voice, reminders) | Keep the app the way you like it |
| Internal ad counters | Respect the advertising frequency caps |

None of this leaves the device on our initiative. If you use Android's automatic
backup, the system itself may copy your progress and preferences to your Google
account — that is an Android feature and is governed by Google's privacy policy.
Consent state and advertising data are **excluded** from that backup.

## 3. Third-party services the application uses

Sinal Verde includes libraries (SDKs) from Google. They run inside the application and
**collect data on their own account**, as processors or as independent controllers, as
the case may be. We only receive aggregated, anonymous reports — never any individual's
raw data.

The table below lists **every** third-party SDK the application uses or may use.

| Service | What it processes | Provider's policy |
|---|---|---|
| Google AdMob / Google Mobile Ads | Device or other identifiers (incl. the Advertising ID), app and ad interactions, diagnostic data, **approximate** location derived from the IP address | <https://policies.google.com/technologies/partner-sites> |
| Google User Messaging Platform (UMP) | A record of your consent choice and of the message shown | <https://policies.google.com/privacy> |
| Firebase Analytics | App usage events, device identifiers, approximate country/region | <https://firebase.google.com/support/privacy> |
| Firebase Crashlytics | Crash logs, stack traces, device model, Android and app version, installation identifier | <https://firebase.google.com/support/privacy> |
| Firebase Remote Config | Installation identifier, basic device and app data, in order to deliver the right settings | <https://firebase.google.com/support/privacy> |
| Firebase Cloud Messaging | Device registration token, in order to deliver announcements | <https://firebase.google.com/support/privacy> |
| Firebase Installations | An app installation identifier (a technical ID, not tied to your identity) used by the Firebase services above | <https://firebase.google.com/support/privacy> |
| Firebase Cloud Storage | **Download only** of question-bank updates. IP address and request metadata | <https://firebase.google.com/support/privacy> |

Google's general privacy policy, which covers all of these products, is at
<https://policies.google.com/privacy>.

### 3.1 Advertising (Google AdMob)

The application is supported by ads. **There are no in-app purchases and no
subscription.**

- Advertising may be **personalised** or **non-personalised**, according to your
  choice (section 6). Non-personalised ads still use context and an approximate
  IP-based location to select what to show and to measure fraud and frequency.
- The Android **Advertising ID** may be used. You can reset or delete it at any time
  under **Android Settings → Google → Ads**
  (<https://support.google.com/googleplay/answer/3405269>).
- Your Google ad preferences can be adjusted at <https://myadcenter.google.com>.
- Ads are rated **PG** at most, and the app is declared **not directed to children**.
- This version uses **no mediation**: Google is the only advertising partner.

### 3.2 Statistics and crash reports

Firebase Analytics records technical usage events such as "an exam started" or "the
results screen was opened". Crashlytics sends a report when the app crashes, so that
the problem can be fixed.

By design:

- we **never** record the text you type into search — only a bucketed length of the
  query;
- we **never** record your individual answers or the correct answers;
- we **never** send personal data as an event parameter.

Crashlytics is **switched off** in development and staging builds; it only runs in the
published release.

If the application is built without the Firebase configuration, **none** of these
services starts and the app remains fully functional.

## 4. How long data is kept

| Where | Period |
|---|---|
| Local data on your device | Until you use "Delete my data", clear the app's data in Android settings, or uninstall the application |
| Firebase Analytics | As configured in the Firebase project — at most 14 months for user-level data; aggregated reports are kept longer |
| Crashlytics | Crash reports remain available for approximately 90 days |
| Remote Config, Installations, Cloud Messaging | For as long as the app is installed; the installation identifier is recreated if you clear the data |
| AdMob / Google Ads | Per Google's retention policies described at <https://policies.google.com/technologies/partner-sites> |

## 5. Security

- All of the application's network traffic uses **HTTPS/TLS**, that is, it is
  **encrypted in transit**. Cleartext traffic is disabled in the app's network
  security configuration and only system certificate authorities are accepted.
- Local data lives in the application's private storage, isolated from other apps by
  Android itself.
- The application **does not log** personal data, answers or search queries, and logs
  are stripped from the published release.
- The app **works fully offline**: with no connection you can still take mock exams,
  practise and revise as normal.

No system is perfectly secure, but since we collect no personal data and run no server
of our own, there is essentially nothing on our side to leak.

## 6. Consent: how it is given and how you withdraw it

Where the law of your region requires it (for example in the European Economic Area,
the United Kingdom, Switzerland and certain US states), the application shows a
**Google User Messaging Platform (UMP) consent form** on first launch, where you choose
what you accept.

- No ad request is made before consent allows it.
- Your choice is passed on to Google's services through **Consent Mode v2**
  (`analytics_storage`, `ad_storage`, `ad_user_data`, `ad_personalization`).
- To **change your mind at any time**, open **Settings → Privacy options**
  ("Opções de privacidade") inside the application. That entry appears whenever your
  region requires the option, and it reopens the same form.

In Brazil, the processing carried out by the SDKs does not depend on a UMP form, but
you keep all of the rights in section 7 and can erase everything via section 9.

## 7. Your rights in Brazil — LGPD (Law No. 13.709/2018)

The **Brazilian General Data Protection Law (LGPD)** applies to the processing of data
of people in Brazil.

### 7.1 Our role

Because Sinal Verde **collects no personal data of its own and has no server**, we do
not ourselves carry out any processing of your personal data. The data described in
section 3 is processed by **Google**, acting as an independent processing agent for
those purposes. We nevertheless answer any request you make and help route it.

### 7.2 Legal bases (arts. 7 and 11)

| Purpose | Legal basis |
|---|---|
| Making the app work and storing your progress on the device | Performance of a contract / legitimate interest (art. 7, V and IX) |
| Showing **non-personalised** ads and measuring fraud | Legitimate interest (art. 7, IX), subject to your right to object |
| Showing **personalised** ads | **Consent** (art. 7, I), collected through the UMP form where applicable |
| Usage statistics and crash reports | Legitimate interest (art. 7, IX) |
| Sending announcements by notification | **Consent** — the Android permission is requested in context and the app works if you decline |

### 7.3 Your rights (art. 18)

At any time you may request:

1. **confirmation** that processing exists;
2. **access** to the data;
3. **correction** of incomplete, inaccurate or out-of-date data;
4. **anonymisation, blocking or deletion** of data that is unnecessary, excessive or
   processed unlawfully;
5. **portability** to another provider;
6. **deletion** of data processed on the basis of consent;
7. **information** about whom we share data with (section 3 already answers this);
8. **information** about the possibility of refusing consent and its consequences;
9. **withdrawal of consent** (section 6);
10. **review** of automated decisions — Sinal Verde makes **no** automated decisions
    affecting you.

The fastest way to exercise items 4 and 6 is the **Settings → Delete my data**
function itself (section 9), which is immediate and requires no request. For any other
right, write to **talero.dev@gmail.com**; we answer within **15 days**.

### 7.4 Contact and supervisory authority

Privacy contact: **talero.dev@gmail.com**.

If you are not satisfied with our answer, you may complain to the **Brazilian National
Data Protection Authority (ANPD)**: <https://www.gov.br/anpd>.

### 7.5 International transfers

The Google services described in section 3 process data on servers outside Brazil.
Those transfers rely on the contractual safeguards and adequacy mechanisms maintained
by Google, described at <https://policies.google.com/privacy>.

## 8. Rights outside Brazil

### 8.1 Europe and the United Kingdom (GDPR and UK GDPR)

If you are in the European Economic Area, the United Kingdom or Switzerland, you have
the right of access, rectification, erasure, restriction of processing, portability
and **objection** to processing based on legitimate interests, as well as the right to
withdraw consent at any time — without affecting what was already done on that basis.

- The legal bases match those in section 7.2: art. 6(1)(b) for making the app work,
  art. 6(1)(f) for measurement and non-personalised ads, art. 6(1)(a) for personalised
  ads and notifications.
- The UMP form (section 6) is the consent and withdrawal mechanism.
- You may complain to your national data protection authority. The European list is at
  <https://www.edpb.europa.eu/about-edpb/about-edpb/members_en>; in the United Kingdom,
  the ICO: <https://ico.org.uk>.
- We carry out no profiling with legal effects on you.

### 8.2 United States

If you live in California, Colorado, Connecticut, Virginia, Utah, Texas or another
state with a consumer privacy law, you may have the right to know which categories of
data are collected, to request deletion or correction, to obtain a copy, and to opt
out of the "sale" or "sharing" of personal data and of targeted behavioural
advertising. **We do not sell personal data and we receive no payment for sharing
it.** Personalised advertising served by Google may, however, fall within the legal
definitions of "sale" or "sharing" in some states: in those cases the application
shows the appropriate UMP message, and you can opt out there or under
**Settings → Privacy options**. We do not discriminate against anyone who exercises
these rights. Requests may be sent to **talero.dev@gmail.com**.

## 9. "Delete my data" — exactly what happens

Under **Settings → Delete my data** ("Excluir meus dados"), after a confirmation
dialog, the application immediately erases:

1. **the local Room databases** — the progress database (answers, attempts, mock
   exams, per-topic statistics, spaced-repetition cards and favourites) and the
   content imported into the content database;
2. **all DataStore preferences** — theme, text size, language, read-aloud voice and
   speed, reminders, onboarding state and ad counters;
3. **the Firebase Analytics data held on your device**, via `resetAnalyticsData()`,
   which discards the app instance identifier and any pending events.

The operation is **permanent and cannot be undone**: your study history is lost. It
does not reach data that has already left the device and sits in Google's systems —
for that, use the Google channels listed in section 3 or write to **talero.dev@gmail.com**.

Uninstalling the application also removes all local data.

## 10. Children

Sinal Verde is **not directed to children**. The target audience declared on Google
Play is **18 and over**, consistent with the minimum driving-licence age in Brazil,
and the application **does not take part in Google Play's Families (Designed for
Families) programme**.

We do not knowingly collect data from anyone under 18. The app is also declared **not
child-directed** to the ads SDK (`tagForChildDirectedTreatment = false`) and **not
intended for users under the age of consent**. If you are responsible for a minor and
believe they have provided us with data, write to **talero.dev@gmail.com** and we will
arrange deletion.

## 11. Android permissions

The application declares only:

| Permission | Why |
|---|---|
| `INTERNET` | Ads, remote configuration, statistics and content updates |
| `ACCESS_NETWORK_STATE` | Knowing whether there is a connection before using the network |
| `com.google.android.gms.permission.AD_ID` | Access to the Advertising ID, required by the ads SDK |
| `POST_NOTIFICATIONS` | Study reminders and announcements — requested in context; declining does not prevent use of the app |

We use no location, camera, microphone, contacts, files, foreground services, exact
alarms or accessibility services.

## 12. External links and content

The application links to official government pages (gov.br) as the source of the study
content, and to the Google policies cited here. We do not control those sites and are
not responsible for their privacy practices.

## 13. Changes to this policy

If this policy changes, the "Last updated" date and the version number below will
change, and the new version takes effect once published at https://github.com/talero-dev/sinalverde-privacy-policy.
Material changes will be announced inside the application.

## 14. Contact

Questions, requests to exercise your rights, or complaints:

**Data controller:** Talero
**Privacy contact:** talero.dev@gmail.com

---

**Last updated: November 10, 2026**
**Document version: 1.0.0 — corresponds to application version 1.0.0 (versionCode 10000)**

---

# Política de Privacidade (Português) — Sinal Verde: Simulado Detran

**Aplicativo:** Sinal Verde: Simulado Detran
**Identificador na Google Play:** `com.talero.sinalverde`
**Responsável pelo tratamento (controlador):** Talero
**Contato:** talero.dev@gmail.com
**Endereço público desta política:** https://github.com/talero-dev/sinalverde-privacy-policy

---

## Em resumo

- O Sinal Verde **não pede cadastro, não cria conta e não pede seu nome, CPF, e-mail
  ou telefone.**
- **Nós não coletamos dados pessoais seus.** Suas respostas, seus simulados e seu
  progresso ficam **só no seu aparelho**.
- O app **funciona inteiramente offline**. A internet é usada apenas para exibir
  anúncios, buscar configurações remotas e enviar estatísticas de uso e relatórios de
  falha — nada disso é obrigatório para estudar.
- O app **exibe anúncios** (Google AdMob). A publicidade e as ferramentas de medição
  do Google coletam dados próprios, descritos em detalhe abaixo.
- Você pode **rever ou retirar seu consentimento** a qualquer momento e **apagar tudo**
  em **Configurações → Excluir meus dados**.

---

## 1. Quem somos e a quem esta política se aplica

Esta política explica como o aplicativo **Sinal Verde: Simulado Detran** trata dados.
Ela vale para o aplicativo Android distribuído na Google Play sob o identificador
`com.talero.sinalverde` e para nenhum outro serviço.

O Sinal Verde é um **aplicativo independente de estudo**. Ele **não tem vínculo** com
o Senatran, com o Ministério dos Transportes, com nenhum DETRAN estadual nem com
qualquer outro órgão público. Ele não emite, consulta nem altera documentos oficiais.

> **Aviso sobre o conteúdo desta versão:** o banco de questões embarcado nesta versão
> é uma **amostra de desenvolvimento não oficial**, e o próprio aplicativo mostra um
> aviso dizendo isso. Esse ponto é de conteúdo, não de privacidade.

## 2. O que nós coletamos: nada

Nós, Talero, **não coletamos, não recebemos e não armazenamos
nenhum dado pessoal seu**. Não existe servidor nosso: o Sinal Verde não tem backend
próprio.

O aplicativo **não tem contas nem login**. Não pedimos e não temos acesso a:

- nome, e-mail, telefone, CPF, número de CNH ou qualquer documento;
- sua agenda, seus contatos, suas fotos, seus arquivos, sua câmera ou seu microfone;
- sua localização precisa (GPS).

### 2.1 O que fica guardado no seu aparelho

Para que o app funcione, estas informações são gravadas **localmente**, em bancos de
dados Room e em preferências DataStore dentro da área privada do aplicativo:

| O que | Para quê |
|---|---|
| Banco de questões, temas e placas | Permitir o estudo offline |
| Respostas dadas, acertos e erros | Montar o caderno de erros e as estatísticas |
| Simulados realizados, notas e tempos | Mostrar seu histórico e o índice de prontidão |
| Cartões de revisão espaçada e favoritas | Organizar a revisão |
| Preferências (tema, tamanho do texto, idioma, voz da leitura, lembretes) | Manter o app do seu jeito |
| Contadores internos de anúncios | Respeitar os limites de frequência da publicidade |

Nada disso sai do aparelho por nossa iniciativa. Se você usar o backup automático do
Android, o próprio sistema pode copiar seu progresso e suas preferências para a sua
conta Google — isso é um recurso do Android e é regido pela política de privacidade do
Google. O estado de consentimento e os dados de publicidade ficam **excluídos** desse
backup.

## 3. Serviços de terceiros que o aplicativo usa

O Sinal Verde inclui bibliotecas (SDKs) do Google. Elas rodam dentro do aplicativo e
**coletam dados por conta própria**, como operadores ou controladores independentes,
conforme o caso. Nós só recebemos relatórios agregados e anônimos — nunca o dado bruto
de uma pessoa.

A tabela abaixo lista **todos** os SDKs de terceiros que o aplicativo usa ou pode usar.

| Serviço | O que processa | Política do fornecedor |
|---|---|---|
| Google AdMob / Google Mobile Ads | Identificadores do dispositivo (incl. o Identificador de Publicidade), interações com o app e com os anúncios, dados de diagnóstico, localização **aproximada** derivada do endereço IP | <https://policies.google.com/technologies/partner-sites> |
| Google User Messaging Platform (UMP) | Registro da sua escolha de consentimento e do estado da mensagem exibida | <https://policies.google.com/privacy> |
| Firebase Analytics | Eventos de uso do app, identificadores do dispositivo, país/região aproximados | <https://firebase.google.com/support/privacy> |
| Firebase Crashlytics | Registros de falha, rastreamentos de pilha, modelo do aparelho, versão do Android e do app, identificador de instalação | <https://firebase.google.com/support/privacy> |
| Firebase Remote Config | Identificador de instalação, dados básicos do aparelho e do app, para entregar as configurações certas | <https://firebase.google.com/support/privacy> |
| Firebase Cloud Messaging | Token de registro do aparelho, para entregar avisos | <https://firebase.google.com/support/privacy> |
| Firebase Installations | Um identificador de instalação do app (ID técnico, não ligado à sua identidade) usado pelos serviços Firebase acima | <https://firebase.google.com/support/privacy> |
| Firebase Cloud Storage | **Somente download** de atualizações do banco de questões. Endereço IP e metadados da requisição | <https://firebase.google.com/support/privacy> |

A política de privacidade geral do Google, que cobre todos esses produtos, está em
<https://policies.google.com/privacy>.

### 3.1 Publicidade (Google AdMob)

O aplicativo se sustenta com anúncios. **Não há compras dentro do app e não há
assinatura.**

- A publicidade pode ser **personalizada** ou **não personalizada**, conforme a sua
  escolha (seção 6). Anúncios não personalizados ainda usam o contexto e uma
  localização aproximada por IP para escolher o que exibir e para medir fraude e
  frequência.
- O **Identificador de Publicidade (Advertising ID)** do Android pode ser usado.
  Você pode zerá-lo ou excluí-lo a qualquer momento em
  **Configurações do Android → Google → Anúncios**
  (<https://support.google.com/googleplay/answer/3405269>).
- Suas preferências de anúncios do Google podem ser ajustadas em
  <https://myadcenter.google.com>.
- Os anúncios são classificados no máximo como **PG**, e o app é declarado como **não
  direcionado a crianças**.
- Nesta versão **não há mediação** com outras redes de publicidade: o único parceiro
  de anúncios é o Google.

### 3.2 Estatísticas e relatórios de falha

O Firebase Analytics registra eventos técnicos de uso, como "um simulado começou" ou
"a tela de resultados foi aberta". O Crashlytics envia um relatório quando o app
quebra, para que o problema possa ser corrigido.

Por decisão de projeto:

- **nunca** registramos o texto que você digita na busca — apenas uma faixa de
  tamanho da consulta;
- **nunca** registramos as suas respostas individuais nem o gabarito;
- **nunca** enviamos dados pessoais como parâmetro de evento.

O Crashlytics fica **desligado** nas versões de desenvolvimento e de homologação; ele
só funciona na versão publicada.

Se o aplicativo for compilado sem a configuração do Firebase, **nenhum** desses
serviços é iniciado e o app continua funcionando por completo.

## 4. Por quanto tempo os dados ficam guardados

| Onde | Prazo |
|---|---|
| Dados locais no seu aparelho | Até você usar "Excluir meus dados", limpar os dados do app nas configurações do Android ou desinstalar o aplicativo |
| Firebase Analytics | Conforme o prazo configurado no projeto Firebase — no máximo 14 meses para dados de nível de usuário; os relatórios agregados são mantidos por mais tempo |
| Crashlytics | Os relatórios de falha ficam disponíveis por aproximadamente 90 dias |
| Remote Config, Installations, Cloud Messaging | Enquanto o app estiver instalado; o identificador de instalação é recriado se você apagar os dados |
| AdMob / Google Ads | Conforme as políticas de retenção do Google descritas em <https://policies.google.com/technologies/partner-sites> |

## 5. Segurança

- Todo tráfego de rede do aplicativo usa **HTTPS/TLS**, ou seja, é **criptografado em
  trânsito**. O tráfego em texto puro está desativado na configuração de segurança de
  rede do app e apenas autoridades certificadoras do sistema são aceitas.
- Os dados locais ficam na área privada do aplicativo, isolada de outros apps pelo
  próprio Android.
- O aplicativo **não registra em log** dados pessoais, respostas ou consultas de
  busca, e os logs são removidos na versão publicada.
- O app **funciona integralmente offline**: sem internet, você continua fazendo
  simulados, treinos e revisões normalmente.

Nenhum sistema é perfeitamente seguro, mas, como não coletamos dados pessoais e não
mantemos servidor próprio, praticamente não há o que vazar do nosso lado.

## 6. Consentimento: como damos e como você retira

Quando a lei da sua região exige (por exemplo, no Espaço Econômico Europeu, no Reino
Unido, na Suíça e em determinados estados norte-americanos), o aplicativo exibe, na
primeira abertura, um **formulário de consentimento do Google User Messaging Platform
(UMP)**, onde você escolhe o que aceita.

- Nenhum pedido de anúncio é feito antes de o consentimento permitir.
- Sua escolha é repassada aos serviços do Google pelo **Consent Mode v2**
  (`analytics_storage`, `ad_storage`, `ad_user_data`, `ad_personalization`).
- Para **mudar de ideia a qualquer momento**, abra
  **Configurações → Opções de privacidade** dentro do aplicativo. Essa entrada aparece
  sempre que a sua região exigir a opção, e reabre o mesmo formulário.

No Brasil, o tratamento de dados feito pelos SDKs não depende de um formulário do UMP,
mas você mantém todos os direitos da seção 7 e pode apagar tudo pela seção 9.

## 7. Seus direitos no Brasil — LGPD (Lei nº 13.709/2018)

A **Lei Geral de Proteção de Dados Pessoais (LGPD)** se aplica ao tratamento de dados
de pessoas no Brasil.

### 7.1 Nosso papel

Como o Sinal Verde **não coleta dados pessoais próprios e não tem servidor**, não
realizamos, por conta própria, tratamento de dados pessoais seus. Os dados descritos
na seção 3 são tratados pelo **Google**, que atua como agente de tratamento
independente para essas finalidades. Ainda assim, respondemos a qualquer pedido seu e
ajudamos a encaminhá-lo.

### 7.2 Bases legais (arts. 7º e 11)

| Finalidade | Base legal |
|---|---|
| Fazer o app funcionar e guardar seu progresso no aparelho | Execução de contrato / legítimo interesse (art. 7º, V e IX) |
| Exibir anúncios **não personalizados** e medir fraude | Legítimo interesse (art. 7º, IX), com o seu direito de oposição |
| Exibir anúncios **personalizados** | **Consentimento** (art. 7º, I), coletado pelo formulário do UMP onde aplicável |
| Estatísticas de uso e relatórios de falha | Legítimo interesse (art. 7º, IX) |
| Enviar avisos por notificação | **Consentimento** — a permissão do Android é pedida em contexto e o app funciona se você negar |

### 7.3 Seus direitos (art. 18)

Você pode, a qualquer momento, pedir:

1. **confirmação** de que existe tratamento;
2. **acesso** aos dados;
3. **correção** de dados incompletos, inexatos ou desatualizados;
4. **anonimização, bloqueio ou eliminação** de dados desnecessários, excessivos ou
   tratados em desconformidade com a lei;
5. **portabilidade** a outro fornecedor;
6. **eliminação** dos dados tratados com base no consentimento;
7. **informação** sobre com quem compartilhamos dados (a seção 3 já responde);
8. **informação** sobre a possibilidade de não consentir e as consequências disso;
9. **revogação do consentimento** (seção 6);
10. **revisão** de decisões automatizadas — o Sinal Verde **não toma** decisões
    automatizadas que afetem você.

A forma mais rápida de exercer os itens 4 e 6 é a própria função
**Configurações → Excluir meus dados** (seção 9), que é imediata e não depende de
pedido. Para qualquer outro direito, escreva para **talero.dev@gmail.com**; respondemos
em até **15 dias**.

### 7.4 Contato e autoridade

Contato para privacidade: **talero.dev@gmail.com**.

Se você não ficar satisfeito com a nossa resposta, pode reclamar à **Autoridade
Nacional de Proteção de Dados (ANPD)**: <https://www.gov.br/anpd>.

### 7.5 Transferência internacional

Os serviços do Google descritos na seção 3 processam dados em servidores fora do
Brasil. Essas transferências se apoiam nas garantias contratuais e nos mecanismos de
adequação mantidos pelo Google, descritos em <https://policies.google.com/privacy>.

## 8. Direitos fora do Brasil

### 8.1 Europa e Reino Unido (GDPR e UK GDPR)

Se você estiver no Espaço Econômico Europeu, no Reino Unido ou na Suíça, você tem
direito de acesso, retificação, apagamento, limitação do tratamento, portabilidade e
**oposição** ao tratamento baseado em legítimo interesse, além do direito de retirar o
consentimento a qualquer momento — sem prejuízo do que já foi feito com base nele.

- As bases legais correspondem às da seção 7.2: art. 6(1)(b) para o funcionamento do
  app, art. 6(1)(f) para medição e anúncios não personalizados, art. 6(1)(a) para
  anúncios personalizados e notificações.
- O formulário do UMP (seção 6) é o mecanismo de consentimento e de retirada.
- Você pode reclamar à autoridade de proteção de dados do seu país. A lista europeia
  está em <https://www.edpb.europa.eu/about-edpb/about-edpb/members_en>; no Reino
  Unido, o ICO: <https://ico.org.uk>.
- Não realizamos definição de perfil com efeitos jurídicos sobre você.

### 8.2 Estados Unidos

Se você mora na Califórnia, no Colorado, em Connecticut, em Virgínia, em Utah, no
Texas ou em outro estado com lei de privacidade do consumidor, você pode ter direito
de saber quais categorias de dados são coletadas, de solicitar a exclusão ou a
correção, de receber uma cópia e de recusar a "venda" ou o "compartilhamento" de dados
pessoais e a publicidade comportamental direcionada. **Nós não vendemos dados
pessoais e não recebemos pagamento por compartilhá-los.** A publicidade personalizada
servida pelo Google pode, no entanto, se enquadrar nas definições legais de "venda" ou
"compartilhamento" em alguns estados: nesses casos, o aplicativo exibe a mensagem
apropriada do UMP, e a recusa pode ser feita ali ou em **Configurações → Opções de
privacidade**. Não discriminamos quem exerce esses direitos. Pedidos podem ser
enviados para **talero.dev@gmail.com**.

## 9. "Excluir meus dados" — o que exatamente acontece

Em **Configurações → Excluir meus dados**, após uma caixa de confirmação, o aplicativo
apaga imediatamente:

1. **os bancos de dados Room locais** — o banco de progresso (respostas, tentativas,
   simulados, estatísticas por tema, cartões de revisão espaçada e favoritas) e o
   conteúdo importado no banco de conteúdo;
2. **todas as preferências do DataStore** — tema, tamanho do texto, idioma, voz e
   velocidade da leitura, lembretes, estado de onboarding e contadores de anúncios;
3. **os dados do Firebase Analytics do seu aparelho**, com
   `resetAnalyticsData()`, o que descarta o identificador de instância e os eventos
   pendentes.

A operação é **definitiva e não tem desfazer**: seu histórico de estudo é perdido.
Ela não alcança dados que já tenham saído do aparelho e estejam nos sistemas do
Google — para esses, use os canais do Google indicados na seção 3 ou escreva para
**talero.dev@gmail.com**.

Desinstalar o aplicativo também remove todos os dados locais.

## 10. Crianças

O Sinal Verde **não é direcionado a crianças**. O público-alvo declarado na Google
Play é de **18 anos ou mais**, coerente com a idade mínima para habilitação no Brasil,
e o aplicativo **não participa do programa Famílias (Designed for Families)** da
Google Play.

Não coletamos conscientemente dados de menores de 18 anos. O app é declarado como
**não direcionado a crianças** também para o SDK de anúncios
(`tagForChildDirectedTreatment = false`) e como **não destinado a usuários abaixo da
idade de consentimento**. Se você é responsável por um menor e acredita que ele nos
forneceu algum dado, escreva para **talero.dev@gmail.com** e providenciaremos a
exclusão.

## 11. Permissões do Android

O aplicativo declara apenas:

| Permissão | Para quê |
|---|---|
| `INTERNET` | Anúncios, configurações remotas, estatísticas e atualização de conteúdo |
| `ACCESS_NETWORK_STATE` | Saber se há conexão antes de tentar usar a rede |
| `com.google.android.gms.permission.AD_ID` | Acesso ao Identificador de Publicidade, exigido pelo SDK de anúncios |
| `POST_NOTIFICATIONS` | Lembretes de estudo e avisos — pedida em contexto; negar não impede o uso do app |

Não usamos localização, câmera, microfone, contatos, arquivos, serviços em primeiro
plano, alarmes exatos nem serviços de acessibilidade.

## 12. Links e conteúdos externos

O aplicativo aponta para páginas oficiais do governo (gov.br) como fonte do conteúdo
de estudo e para as políticas do Google citadas aqui. Não controlamos esses sites e
não respondemos pelas práticas de privacidade deles.

## 13. Alterações nesta política

Se esta política mudar, a data de "Última atualização" e o número de versão abaixo
serão alterados, e a nova versão passará a valer a partir da publicação em
https://github.com/talero-dev/sinalverde-privacy-policy. Mudanças relevantes serão informadas dentro do
aplicativo.

## 14. Contato

Dúvidas, pedidos de exercício de direitos ou reclamações:

**Controlador dos dados:** Talero
**Contato de privacidade:** talero.dev@gmail.com

---

**Última atualização: 10 de novembro de 2026**
**Versão do documento: 1.0.0 — corresponde à versão 1.0.0 (versionCode 10000) do aplicativo**
