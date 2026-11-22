# Política de privacidade do Call Boring

Atualizado em 22/11/2026

Esta política explica quais dados o app Call Boring (`com.cavazzani.callboring`) usa, para quê, e quais são os seus direitos. O responsável pelo tratamento é Guilherme Abreu Cavazzani, contato cavazzani.projetos@gmail.com.

## O essencial

- Seus contatos e o histórico de ligações ficam **só neste celular** e nunca são enviados a servidor nenhum.
- O app não copia sua agenda. O **Modo IA** é opcional e só liga com o seu consentimento; ele também trabalha só no aparelho, guarda da agenda apenas um resumo estatístico, e você apaga o que ele aprendeu quando quiser.
- O app não pede nome, e-mail, telefone nem cadastro.
- O app registra eventos de uso da interface (Firebase Analytics), sem número, nome nem histórico, e o Google deriva deles uma localização aproximada. Você pode desligar isso na Ajuda.

## Permissões que o app pede

- **Telefone (READ_PHONE_STATE):** para saber que uma ligação está chegando. Com o Modo IA ligado, também para saber se uma ligação que passou pelo Filtro foi atendida ou perdida e quanto tempo durou.
- **Contatos (READ_CONTACTS):** para saber se o número que liga é de um contato. Contatos tocam sempre. Com o Modo IA ligado, também para montar o resumo estatístico descrito em "Modo IA".
- **Atender ligações (ANSWER_PHONE_CALLS):** para o Filtro poder recusar a ligação de um Desconhecido.
- **Função de triagem de chamadas:** é o papel do Android que permite ao app analisar a ligação recebida antes de tocar. Com esse papel, o Android também informa ao app as ligações que você faz; com o Modo IA ligado, o app registra as que você faz para números fora dos seus contatos, para saber se você ligou de volta. Você concede esse papel nos ajustes do sistema.
- **Notificações (POST_NOTIFICATIONS):** para mostrar avisos do app, entre eles os avisos do Modo IA.
- **Iniciar com o aparelho (RECEIVE_BOOT_COMPLETED):** para que o app volte a funcionar depois de reiniciar o celular.
- **Ignorar otimização de bateria (REQUEST_IGNORE_BATTERY_OPTIMIZATIONS):** para o Android não suspender o Filtro para economizar bateria.

Você pode retirar qualquer permissão a qualquer momento nos ajustes do Android. Sem algumas delas, o Filtro deixa de funcionar.

## Dados que ficam só no aparelho

Estes dados são gravados no armazenamento do próprio app e nunca saem do aparelho:

- **Contatos:** consultados no momento da ligação, para saber se o número é de um contato. O app não copia sua agenda. Com o Modo IA ligado, ele guarda da agenda só o resumo estatístico descrito em "Modo IA".
- **Histórico de ligações:** lista das ligações recebidas que o app analisou, inclusive as de contatos, com o número completo, data, hora e resultado (tocou, recusada ou silenciada; com o Modo IA, também se foi liberada pela IA). Quando quem ligou é um contato, o histórico guarda também o nome dele. Alimenta a tela inicial e o widget.
- **Dados do Modo IA** (só com o Modo IA ligado): o resumo estatístico dos contatos, o histórico das ligações analisadas com o desfecho de cada uma, as ligações que você faz para números fora dos contatos, as suas correções e o que a IA aprendeu com eles. Estão detalhados em "Modo IA".
- **Lista pessoal:** os números que você escolheu para tocar sempre.
- **Regiões liberadas (DDDs) e ajustes:** Filtro ligado ou desligado, Silenciar, tema, contagem do Limite diário, se o Pro está ativo, os ajustes do Modo IA e a versão do texto do Modo IA que você aceitou.

Nenhum desses dados é enviado, nem para backup, nem para análise, nem para formar uma base de números. Os dados do Modo IA e o arquivo de ajustes do app ficam fora do backup automático do Google e da transferência para outro aparelho.

## Modo IA

O Modo IA é uma função **opcional**, desligada até você ativá-la. Ele aprende quais ligações de Desconhecidos parecem importantes, para deixá-las tocar. Tudo acontece neste celular: **nada do Modo IA é enviado a servidor nenhum**.

**Consentimento.** O Modo IA só liga depois que você aceita o texto que o app mostra na ativação; essa tela tem um link para esta seção. Esse consentimento é separado da aceitação destes textos legais e é a base legal desse tratamento (consentimento, art. 7º, I, da LGPD). O app guarda a versão do texto que você aceitou.

Com o Modo IA ligado, o app trata no aparelho:

- **Resumo estatístico dos contatos:** os contatos do **perfil pessoal** são analisados no aparelho, e o app guarda deles só contagens por DDD e por faixa de numeração (o DDD e até os 6 primeiros dígitos depois do DDD). Desse resumo não fazem parte nomes nem números completos de contatos. Contatos do perfil de trabalho e de contas de trabalho que o app consegue identificar, como contas Exchange, ficam de fora.
- **Histórico das ligações analisadas:** o número que ligou, data e hora, o chip que recebeu, se a operadora verificou o número de quem ligou, o que o Filtro e a IA decidiram e por quê, os avisos que o app já mostrou sobre a ligação (para não repeti-los) e o desfecho: se a ligação foi atendida ou perdida e quanto tempo durou, medido pelo estado do telefone. Também anota se você ligou de volta para o número ou o salvou nos contatos depois, porque isso indica que a ligação era importante.
- **Ligações que você faz:** as ligações que você faz para números fora dos seus contatos, com número, data e hora, para saber se você retornou uma ligação.
- **Comparação com o seu número:** o app compara o número que ligou com o número da sua própria linha, para perceber números falsos parecidos com o seu. Essa comparação é feita no aparelho, e o número da sua linha não é enviado a lugar nenhum.
- **Suas correções:** quando você marca uma ligação como "Era importante" ou "Não era importante".
- **O que a IA aprendeu:** os parâmetros calculados a partir desses dados, que não contêm nomes nem números de contatos.

**Nome do contato.** Os avisos do Modo IA nunca mostram o nome de um contato: quando o número que ligou parece com o de um contato, o aviso diz só "parecido com um contato seu". O nome aparece apenas dentro do app, ao revisar a ligação; ele é lido da agenda na hora, e o Modo IA não o grava.

**Apagar e desligar.** Em **Modo IA › Apagar o que a IA aprendeu**, você apaga de uma vez o resumo dos contatos, o histórico das ligações analisadas, as ligações que você fez registradas pelo Modo IA, as correções e o que a IA aprendeu, e as marcas do Modo IA saem do histórico de ligações. **Desligar o Modo IA** revoga o consentimento e apaga esses mesmos dados. A Lista pessoal não depende da IA: ela continua até você limpá-la na tela da Lista pessoal.

## Firebase Analytics

O app usa o Firebase Analytics (Google) para entender como a interface é usada, por exemplo toques em botões e abertura da página do app na loja. Esses eventos **não contêm número de telefone, nome de contato nem o histórico de ligações**. Sobre o Modo IA, os eventos dizem que ele foi ligado ou desligado, que houve uma correção, com o tipo da correção, sem dizer de qual ligação ou número, e quantas ligações a IA liberou, em contagem total. Eles nunca contêm o número, o nome, a marcação de uma ligação nem a pontuação que a IA deu a ela. Além desses eventos, o Firebase registra eventos técnicos automáticos, como a abertura de telas. O Firebase associa os eventos a um identificador da instalação do aplicativo no aparelho e a dados técnicos do dispositivo, como modelo, marca e versão do Android. A partir do endereço IP, o Google também deriva uma localização aproximada (cidade ou região), sem usar o GPS e sem pedir a permissão de localização. O app **não coleta nem usa o ID de publicidade** do Android e não usa o Firebase para publicidade.

Para desligar, abra **Ajuda** e desative **Compartilhar dados de uso**.

## Notificações (Firebase Cloud Messaging)

Para receber notificações, o app usa o Firebase Cloud Messaging (Google), que cria um token de notificação para o aparelho. Esse token serve só para entregar as notificações. A permissão de Notificações do Android controla se o app as mostra; o token continua existindo enquanto o app estiver instalado, e o interruptor "Compartilhar dados de uso" não o afeta. Para apagá-lo, desinstale o app.

## Compra do Pro

O Pro é comprado pela Google Play. O pagamento é processado pela Google Play, e o app **não vê** seus dados de pagamento. O app só recebe da loja a confirmação de que a compra existe, para liberar o Pro. A política de privacidade do Google se aplica a essa parte.

## Widget

O widget da tela inicial mostra o estado do Filtro e o resumo do que o Filtro fez, usando os dados que já estão no aparelho. Ele não envia nada para fora.

## Por quanto tempo guardamos os dados

- Os dados do aparelho ficam até você apagá-los: limpando os dados do app nos ajustes do Android ou desinstalando o app.
- No histórico do Modo IA, uma ligação sem correção nem sinal de importância fica por até 120 dias. Uma ligação que você corrigiu, ou que deu sinal de ser importante (você ligou de volta, atendeu por mais tempo ou salvou o número depois), fica por até 1 ano. Nos dois casos, o app apaga as mais antigas quando passa de um número máximo de ligações. Todos os dados do Modo IA são apagados antes disso se você usar "Apagar o que a IA aprendeu" ou desligar o Modo IA.
- A Lista pessoal fica até você remover os números ou limpá-la.
- Os eventos do Firebase Analytics seguem os prazos de retenção configurados no Firebase, e não incluem seu nome nem seu telefone.

## Crianças

O app não é voltado a menores de 13 anos e não coleta dados pessoais de crianças de propósito. Menores de 18 anos devem usá-lo com o consentimento de um responsável.

## Seus direitos (LGPD)

Pela Lei Geral de Proteção de Dados (Lei nº 13.709/2018), você pode pedir: confirmação de que tratamos dados seus, acesso, correção, anonimização, eliminação, informações sobre compartilhamento e revogação de consentimento.

Como os contatos, o histórico e os dados do Modo IA ficam só no seu aparelho, não temos acesso a eles; você os controla e apaga pelo próprio app ou pelos ajustes do Android. Para revogar o consentimento do Modo IA, basta desligá-lo. Para pedidos sobre outros dados, escreva para cavazzani.projetos@gmail.com e responderemos em prazo razoável, dentro do que a lei exige. Você também pode reclamar à Autoridade Nacional de Proteção de Dados (ANPD).

## Mudanças nesta política

Podemos atualizar esta política. A data no topo mostra a versão em vigor. Quando a mudança for relevante, o app avisa você na tela inicial.

## Contato

Guilherme Abreu Cavazzani, cavazzani.projetos@gmail.com
