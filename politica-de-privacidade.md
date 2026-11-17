# Política de privacidade do Call Boring

Atualizado em 17/11/2026

Esta política explica quais dados o app Call Boring (`com.cavazzani.callboring`) usa, para quê, e quais são os seus direitos. O responsável pelo tratamento é Guilherme Abreu Cavazzani, contato cavazzani.projetos@gmail.com.

## O essencial

- Seus contatos e o histórico de ligações ficam **só neste celular** e nunca são enviados a servidor nenhum.
- O app não pede nome, e-mail, telefone nem cadastro.
- O app registra eventos de uso da interface (Firebase Analytics), sem número, nome nem histórico. Você pode desligar isso na Ajuda.

## Permissões que o app pede

- **Telefone (READ_PHONE_STATE):** para saber que uma ligação está chegando.
- **Contatos (READ_CONTACTS):** para saber se o número que liga é de um contato. Contatos tocam sempre.
- **Atender ligações (ANSWER_PHONE_CALLS):** para o Filtro poder recusar a ligação de um Desconhecido.
- **Função de triagem de chamadas:** é o papel do Android que permite ao app analisar a ligação recebida antes de tocar. Você concede nos ajustes do sistema.
- **Notificações (POST_NOTIFICATIONS):** para mostrar avisos do app.
- **Iniciar com o aparelho (RECEIVE_BOOT_COMPLETED):** para que o app volte a funcionar depois de reiniciar o celular.
- **Ignorar otimização de bateria (REQUEST_IGNORE_BATTERY_OPTIMIZATIONS):** para o Android não suspender o Filtro para economizar bateria.

Você pode retirar qualquer permissão a qualquer momento nos ajustes do Android. Sem algumas delas, o Filtro deixa de funcionar.

## Dados que ficam só no aparelho

Estes dados são gravados no armazenamento do próprio app e nunca saem do aparelho:

- **Contatos:** consultados no momento da ligação, só para comparar o número. O app não copia nem guarda sua agenda.
- **Histórico de ligações:** lista dos números analisados pelo Filtro, com data, hora e resultado (tocou, recusada ou silenciada). Alimenta a tela inicial e o widget.
- **Regiões liberadas (DDDs) e ajustes:** Filtro ligado ou desligado, Silenciar, tema, contagem do Limite diário e se o Pro está ativo.

Nenhum desses dados é enviado, nem para backup, nem para análise, nem para formar uma base de números.

## Firebase Analytics

O app usa o Firebase Analytics (Google) para entender como a interface é usada, por exemplo toques em botões e abertura da página do app na loja. Esses eventos **não contêm número de telefone, nome de contato nem o histórico de ligações**. O Firebase pode associar os eventos a um identificador do aplicativo no aparelho e a dados técnicos do dispositivo, como modelo e versão do Android.

Para desligar, abra **Ajuda** e desative **Compartilhar dados de uso**.

## Notificações (Firebase Cloud Messaging)

Para receber notificações, o app usa o Firebase Cloud Messaging (Google), que cria um token de notificação para o aparelho. Esse token serve só para entregar as notificações. A permissão de Notificações do Android controla se o app as mostra; o token continua existindo enquanto o app estiver instalado, e o interruptor "Compartilhar dados de uso" não o afeta. Para apagá-lo, desinstale o app.

## Compra do Pro

O Pro é comprado pela Google Play. O pagamento é processado pela Google Play, e o app **não vê** seus dados de pagamento. O app só recebe da loja a confirmação de que a compra existe, para liberar o Pro. A política de privacidade do Google se aplica a essa parte.

## Widget

O widget da tela inicial mostra o estado do Filtro e o resumo do que o Filtro fez, usando os dados que já estão no aparelho. Ele não envia nada para fora.

## Por quanto tempo guardamos os dados

- Os dados do aparelho ficam até você apagá-los: limpando os dados do app nos ajustes do Android ou desinstalando o app.
- Os eventos do Firebase Analytics seguem os prazos de retenção configurados no Firebase, e não incluem seu nome nem seu telefone.

## Crianças

O app não é voltado a menores de 13 anos e não coleta dados pessoais de crianças de propósito. Menores de 18 anos devem usá-lo com o consentimento de um responsável.

## Seus direitos (LGPD)

Pela Lei Geral de Proteção de Dados (Lei nº 13.709/2018), você pode pedir: confirmação de que tratamos dados seus, acesso, correção, anonimização, eliminação, informações sobre compartilhamento e revogação de consentimento.

Como os contatos e o histórico ficam só no seu aparelho, não temos acesso a eles; você os controla e apaga pelo próprio app ou pelos ajustes do Android. Para pedidos sobre outros dados, escreva para cavazzani.projetos@gmail.com e responderemos em prazo razoável, dentro do que a lei exige. Você também pode reclamar à Autoridade Nacional de Proteção de Dados (ANPD).

## Mudanças nesta política

Podemos atualizar esta política. A data no topo mostra a versão em vigor. Quando a mudança for relevante, o app avisa você na tela inicial.

## Contato

Guilherme Abreu Cavazzani, cavazzani.projetos@gmail.com
