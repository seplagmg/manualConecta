---
description: >-
  Foi desenvolvida uma nova funcionalidade para permitir aos gestores suspender
  um atendente ou especialista de sua equipe de roteiros específicos.
---

# 🚫 Suspender usuário por roteiro

**O atendente suspenso de roteiros específicos continua ativo dentro do sistema, recebendo chamados, só não receberá chamados dos roteiros em que está suspenso. O gestor pode retirar a suspensão para retornar o atendente ao fluxo de atendimento daquele roteiro.**

1. O atendente suspenso de roteiros específicos continua ativo dentro do sistema, recebendo chamados, só não receberá chamados dos roteiros em que está suspenso. O gestor pode retirar a suspensão para retornar o atendente ao fluxo de atendimento daquele roteiro.

<figure><img src="../.gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>

2. A opção “Suspender usuário de roteiro” levará a uma nova tela. Essa nova tela deve exibir os seguintes dados do atendente: “Nome do usuário”, “Masp”, “Admissão”, “Instituição” e “Unidade”.

<figure><img src="../.gitbook/assets/image (195).png" alt=""><figcaption></figcaption></figure>

3. A nova tela “Suspender usuário de roteiro específico” possue uma tabela com todos os roteiros em que o atendente está cadastrado, com duas colunas adicionais à extrema direita: “Status” e “Ações”

<figure><img src="../.gitbook/assets/image (190).png" alt=""><figcaption></figcaption></figure>

a) Na coluna Status o sistema indica se o atendente está “Ativo” ou “Suspenso” em cada roteiro.

b) Na coluna “Ações” o sistema exibe um botão de “Suspender” (botão amarelo com ícone de pause) se o status do atendente no roteiro for “Ativo”. Deve exibir um botão de “Retirar suspensão” (botão verde com ícone de play) se o status do atendente for “Suspenso”.

![](<../.gitbook/assets/image (192).png>)

1\.      O usuário suspenso de um roteiro X não receberá mais chamados desse roteiro na distribuição automática.&#x20;

2\.      Os chamados do roteiro X, do qual o atendente foi suspenso, que estiverem com o atendente suspenso não são redistribuídos automaticamente. Caso seja necessário, o gestor pode redistribuir esses chamados a partir da caixa da unidade.

3\.      Se o atendente suspenso era o único atendente ativo do roteiro em um nível, qualquer chamado daquele roteiro que chegar no nível irá para a caixa da unidade e deverá ser distribuído manualmente. \
