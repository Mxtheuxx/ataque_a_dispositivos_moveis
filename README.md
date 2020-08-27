# ataque_a_dispositivos_moveis

Formas de ataque a dispositivos moveis (Android e IOS)
	Irei iniciar sobre o tema de ataque a dispositivos moveis de uma forma geral, depois irei falar sobre os ataques a android e o ios.
Dispositivos moveis em geral:

•	Malwares

No caso os malwares funcionam tanto em computadores quanto em dispositivos moveis como por exemplo o celular, alguns tipos de malwares mais famosos em dispositivos moveis são os backdoors, trojan clicker, trojan banker e keyloggers, no caso eu só irei falar como funciona os trojans pois sobre backdoor e keylogger eu já falei no artigo “Tipos_de_Malwares”, o trojan clicker se baseia em fazer o usuário ser redirecionado para um determinado site, no caso ele pode fazer com que o trojan clicker redirecione a vítima para o site de phishing do hacker (Obs: falei sobre phishing no artigo sobre “Social_Engineering”), o trojan banker coleta informações do dispositivo do usuário através de um malware junto dele no caso o "spyware", no caso esse determinado spyware só é ativado quando o dispositivo acessa um app de banco ou um site de banco.

•	Acesso físico direto

O ataque físico ele é bem mais simples que os outros só que com ele é mais garantido o resultado do ataque, sem falar que também ele é um dos ataques mais comuns, pois a maioria usuários deixam os seus celulares sem senhas, pin ou biometria, deixando assim o hacker com uma facilidade maior ao dispositivo.

•	Tapjacking

O ataque tapjacking se baseia no hacker captura o toque da tela do usuário, no caso o hacker pode fazer uma tela fake e quando o usuário for por sua senha na tela original o usuário ser redirecionado para a tela fake. Outra forma desse ataque é a sobreposição de janela, no caso esse tipo de ataque consiste em roubar senhas do usuário, ele é tipo o ataque “Credencial Stealers”.

•	Lançamento de aplicativos

Esse tipo de ataque é muito comum pois os hackers se aproveitam de um lançamento de um determinado jogo ou aplicativo para fazer um malware e divulga esse malware como se fosse o aplicativo que vai ser lançado.

•	Camuflagem de aplicativos

No caso esse tipo de ataque se baseia no malware depois de infectar o dispositivo se passar por um serviço próprio do sistema, excluindo o ícone do aplicativo após a instalação ser concluída pelo o usuário.

•	Attacking SMS

O ataque via sms muitas vezes é utilizado junto com outra forma de ataque, por exemplo a engenharia social, um exemplo sobre o ataque sms seria quando o hacker se passa por uma empresa falando que o usuário precisa confirmar o sms enviando para eles.

•	Bluetooth Attack

- Bluesnarfing
Esse ataque se baseia no hacker ter total acesso ao dispositivo apenas conectado via bluetooth sem a autorização do usuário.

- Bluejacking
Se baseia em um ataque que envia arquivos aos dispositivos mais próximos por via bluetooth.

•	Desatualização de dispositivos

Essa forma de ataque se baseia em um 0day no caso, no caso 0day é uma vulnerabilidade grave em um determinado sistema ou software, em outras palavras é uma vulnerabilidade desconhecida por todos, isso significa que a partir do momento em que a falha for descoberta, o proprietário do software ou sistema tem que fazer uma nova versão do sistema ou software corrigindo o erro da falha 0day da antiga versão. Por isso devemos atualizar sempre os nossos sistemas e softwares quando houver uma nova versão, pois as atualizações servem para corrigir erros, vulnerabilidade e ate adicionar alguma coisa nova.

•	Falha em softwares externos

Falhas em aplicativos externos seriam os que você baixa na loja de aplicativos do seu dispositivo, isso acontece quando um hacker acha vulnerabilidade dentro desse determinado aplicativo e faz um vazamento de dados.

•	Wi-fi públicos 

Acessar wi-fi desprotegidos é uma porta aberta para ser invadido, pois em wi-fi públicos não a senhas então não existe nada que possa bloquear o hacker de ataque quem está dentro da rede. (obs: caso queira saber como funciona um ataque de redes basta olhar o artigo “Man-In-The-Middle-“)

•	Sim Swap

Para ocorrer esse ataque o hacker vai precisar de um cumplice que trabalha dentro de uma empresa de chip, pois o ataque se baseia no hacker acessar aplicativos autenticados utilizando o chip clonado como o por exemplo o aplicativo “WhatsApp”.

•	Ataque via SS7

A vulnerabilidade SS7 é uma vulnerabilidade antiga, no caso primeiro irei explicar o que é ss7: SS7(Signalling System Number 7), traduzindo ficaria "Sistema de Sinalização n°7", é um conjunto de protocolos que permite que redes de telefonia possam trocar informações e que as ligações possam trafegar de maneira transparente. No caso a vulnerabilidade no protocolo ss7 permite o hacker ter acesso ao dispositivo móvel, permite ainda a interceptação de mensagens em aplicativos de mensagens como sms ou whatsapp (obs: essa forma de ataque já foi usada com a ex-presidente dilma)

•	Cryptojacking

O cryptojacking é uma forma de ataque onde o hacker passa um malware para as suas vitimas e esse malware vai usar o dispositivo como forma de minerador, no caso esse tipo de ataque você vê muito em desktop mais em 2018 teve milhares de vítimas em dispositivos moveis.

•	Buffer Overflows

Buffer Overflows traduzindo ficaria (Estouros de buffer) no caso quando um programa tenta armazenar mais dados em um buffer (área de armazenamento temporário) do que deveria, ele sobrescreve a memória adjacente. Isso é causado por um erro de programação, mas esse erro pode levar a um tipo comum de ataque à segurança. Esses estouros de buffer afetam a integridade dos dados e podem levar ao aumento de privilégios ou ataques de execução remota de código em PCs. (Obs: Já estamos vendo alguns estouros de buffer em dispositivos móveis também.)

•	Engenharia Social 

Engenharia social é um conjunto de práticas que exploram a falha humana, no caso a confiança dos usuários para obter informações de determinado sistema ou empresa. (Obs: Caso queira saber mais sobre engenharia social basta ir no artigo que fiz “Social_Engineering”)
(Obs: Todas as formas que falei acima não irei repetir elas, pois já foram ditas, no caso eu poderia falar sobre 0day em android e ios mais como já foi dito no texto não irei repetir as formas de ataques que já foram faladas.)

Android:

•	Ameaças PUP

(PUP) representa (potentially unwanted program), traduzindo ficaria (programa potencialmente indesejado), na maioria das vezes esses "PUP" não são 100% maliciosos, mas esses programas com PUP utilizam grandes quantidades de recursos do sistema, no caso alguns causam spam de e-mails e podem deixa o sistema lento. (Obs: esse tipo de ameaça é tanto em desktop quanto em mobile, mais você observa mais os antivírus falando sobre pup em mobiles)

•	Ataque via MMS

No caso esse ataque se baseia em uma vulnerabilidade na biblioteca de mídia do android, por ela é possível que atacantes enviassem uma mensagem de texto com um malware para qualquer número de celular, mesmo que o usuário não abrisse nem confirmasse o recebimento da mensagem, o malware podia ser implantado dando total acesso a raiz do dispositivo móvel ao hackers(Obs: essa vulnerabilidade foi corrigida rapidamente, mas com ela foi comprovada que dá pra infecta dispositivos por meio de textos).

•	Ataques de manchas

A maioria dos smartphones Android usam a tela de toque para bloquear e desbloquear o telefone, no padrão Android são usados para senhas que são apenas pontos de contato gráficos, o usuário atravessa esses pontos para uma correspondência de padrões bem-sucedida. O invasor usa uma maneira diferente de reconhecer o padrão de senha, como iluminação e câmera com ângulos diferentes, bem como estilos de luz diferentes. Para reconhecer o padrão, diferentes técnicas são usadas para tirar fotos com diferentes iluminação e ângulos, e também realizar alguns experimentos nessas fotos para encontrar o padrão correto.

•	Ataque de privacidade

Esses tipos de ataques estão relacionados à privacidade, no caso quando ocorre algum vazamento de dados confidenciais do usuário, conta bancária, contato do usuário, agenda de reuniões e outras informações da conta social para o invasor.

•	Ataque de escalonamento de privilégio 

Este ataque aconteceu devido a vulnerabilidades no privilégio transitivo do Android que permite que o aplicativo ignore a restrição imposta pela sandbox. Há uma fraqueza em seu mecanismo de autorização, de modo que pode resultar em um ataque de escalonamento de privilégios. 

IOS:

•	Engenharia social

Engenharia social é uma forma de ataque muito usada pelos hackers, pois ela é fácil e pratica, como dito você pode ler o artigo “Social_Engineering” 

•	Malwares/0day

Como já citei forma de ataque 0day e malware no texto irei deixar aqui um tópico sobre isso voltado ao ios: https://www.wired.com/story/ios-attack-watering-hole-project-zero/

Espero ter passado um bom conhecimento sobre algumas formas de ataque a dispositivos moveis, abraços do Mxtheux <3 
