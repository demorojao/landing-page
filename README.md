# landing-page
Design of a landing page for a pet shop made with HTML5 and CSS3</br>

Look at that "master" branch






Clonando com as URLs de HTTPS
As URLs de clone https:// estão disponíveis em todos os repositórios, independentemente da visibilidade. As URLs de clone https:// funcionam mesmo que você esteja protegido por um firewall ou um proxy.

Quando você usar git clone, git fetch, git pull ou git push em um repositório remoto usando URLs HTTPS na linha de comando, o Git solicitará seu nome de usuário e sua senha do GitHub. Quando o Git solicitar sua senha, insira seu personal access token. Como alternativa, você pode usar um auxiliar de credencial como o Gerenciador de Credenciais do Git. A autenticação baseada em senha do Git foi removida para dar lugar a métodos de autenticação mais seguros. Para obter mais informações, veja "Gerenciar seus tokens de acesso pessoal".

Se você estiver acessando uma organização que usa o SSO do SAML e usando um personal access token (classic), será necessário autorizar o personal access token para acessá-la antes de autenticar-se. Para obter mais informações, confira "Sobre a autenticação com logon único de SAML" e "Autorizar o uso de um token de acesso pessoal para uso com logon único SAML".

Dicas:

Você pode usar um auxiliar de credenciais para que o Git se lembre de suas credenciais de GitHub toda vez que falar com GitHub. Para obter mais informações, confira "Armazenar suas credenciais do GitHub no Git".
Para clonar um repositório sem se autenticar no GitHub na linha de comando, use o GitHub Desktop para a clonagem. Para obter mais informações, confira "Clonar um repositório do GitHub para o GitHub Desktop".
Se você prefere usar o SSH mas não consegue se conectar pela porta 22, use o SSH pela porta HTTPS. Para obter mais informações, confira "Usar SSH na porta HTTPS".

Clonar com URLs de SSH
As URLs de SSH fornecem acesso a um repositório do Git via SSH, um protocolo seguro. Para usar estas URLs, gere um par de chaves SSH no computador e adicione a chave pública à sua conta do GitHub.com. Para obter mais informações, confira "Conectar-se ao GitHub com o SSH".

Quando você usar git clone, git fetch, git pullou git push em um repositório remoto usando URLs SSH, precisará inserir uma senha e fornecer sua frase secreta de chave SSH. Para obter mais informações, confira "Trabalhar com frase secreta da chave SSH".

Se você estiver acessando uma organização que usa o SSO (logon único) do SAML, precisará autorizar sua chave SSH a acessar a organização antes de realizar a autenticação. Para obter mais informações, confira "Sobre a autenticação com logon único de SAML" e "Autorizar o uso de uma chave SSH para uso com logon único SAML" na documentação do GitHub Enterprise Cloud.

Dica: use uma URL com SSH para clonar um repositório no computador ou como uma forma segura de implantar seu código em servidores de produção. Você também pode usar o encaminhamento de agente SSH com o seu script de implantação para evitar o gerenciamento de chaves no servidor. Para obter mais informações, confira "Usar o encaminhamento de agente SSH".

Clonar com GitHub CLI
Você também pode instalar o GitHub CLI para usar os fluxos de trabalho do GitHub no seu terminal. Para obter mais informações, confira "Sobre o a CLI do GitHub".
