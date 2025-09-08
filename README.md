# SheGo---UPX-4
SheGo é um aplicativo de caronas voltado para mulheres universitárias, oferecendo segurança e praticidade no deslocamento acadêmico. Desenvolvido em grupo para a disciplina UPX do 4º semestre, o projeto integra programação, design e colaboração em equipe.

-Primeiros Passos: Para quem é iniciante
Se você nunca utilizou o Git ou o GitHub, preparamos um guia rápido para você começar.

1. Criando sua conta no GitHub
O GitHub é a plataforma online onde nosso código ficará armazenado.

Acesse https://github.com/.

Clique em "Sign up" (Inscrever-se) no canto superior direito.

Siga as instruções, preenchendo seu e-mail, criando uma senha e escolhendo um nome de usuário.

Você receberá um e-mail de verificação para confirmar e ativar sua conta.

2. Instalando o Git na sua máquina
O Git é a ferramenta que vamos usar no nosso computador para controlar as versões do código e enviá-las para o GitHub.

Acesse o site oficial: https://git-scm.com/downloads.

O site irá sugerir o download correto para seu sistema operacional (Windows, Mac ou Linux).

Baixe o instalador e siga as instruções. As configurações padrão são suficientes para a maioria dos casos.

3. Configurando o Git localmente
Após a instalação, é importante que você configure seu nome de usuário e e-mail. Eles serão a sua "assinatura" em todas as contribuições que você fizer.

Abra o terminal (ou o Git Bash, que é instalado com o Git no Windows) e execute os seguintes comandos, substituindo os dados de exemplo pelos seus:

git config --global user.name "Seu Nome Completo"
git config --global user.email "seu-email-de-cadastro@exemplo.com"

- Como Contribuir com o Código
Agora que você tem tudo pronto, veja como participar do desenvolvimento.

1. Clonando o Repositório
"Clonar" significa fazer uma cópia do projeto que está no GitHub para a sua máquina.

Na página principal do nosso repositório, clique no botão verde < > Code.

Copie a URL da opção HTTPS.

Abra o terminal, navegue até a pasta onde você guarda seus projetos e execute o comando abaixo:

git clone URL_QUE_VOCE_COPIOU

Isso criará uma pasta chamada Shego com todos os arquivos do projeto.

2. Criando sua Branch de Trabalho (Ramificação)
Para evitar conflitos, nunca trabalharemos diretamente na branch main. Cada nova funcionalidade ou correção deve ser feita em uma "branch" (ramificação) separada.

Acesse a pasta do projeto pelo terminal:

cd Shego

Antes de criar sua branch, garanta que sua main local está atualizada com a do repositório remoto:

git checkout main
git pull origin main

Agora, crie uma nova branch para a sua tarefa. Use um nome descritivo, como feature/tela-cadastro ou fix/bug-login.

git checkout -b nome-da-sua-branch

Este comando único cria a branch e já te move para dentro dela. Todo o trabalho a partir de agora será feito aqui, de forma isolada.

3. Adicionando e "Commitando" suas Alterações
Conforme você desenvolve, precisa salvar seu progresso no histórico do Git. Esse processo tem duas etapas: add e commit.

Depois de criar ou modificar arquivos, use o comando git add para prepará-los para o "commit".

# Para adicionar todos os arquivos modificados de uma vez (mais comum)
git add .

Agora, "comite" suas alterações. O commit é um ponto de salvamento definitivo no histórico. É obrigatório incluir uma mensagem clara e objetiva sobre o que foi feito.

git commit -m "feat: desenvolve estrutura inicial da tela de cadastro"

Dica: Tente seguir um padrão para as mensagens de commit, como: feat: para novas funcionalidades, fix: para correções, docs: para documentação, etc.

4. Enviando suas Alterações para o GitHub (Push)
Seus commits ainda estão apenas na sua máquina. Para que a equipe veja seu trabalho, você precisa enviá-lo para o repositório no GitHub com o comando git push.

Na primeira vez que enviar sua nova branch, use:

git push -u origin nome-da-sua-branch

Nas próximas vezes que for enviar novos commits da mesma branch, basta usar:

git push

5. Criando um Pull Request (PR)
O Pull Request (PR) é o seu pedido formal para integrar o código da sua branch na branch main. É o momento em que a equipe pode revisar seu trabalho, sugerir melhorias e aprovar a inclusão.

Após fazer o push, acesse a página do nosso repositório no GitHub.

O GitHub mostrará um aviso com o nome da sua branch e um botão Compare & pull request. Clique nele.

Dê um título claro ao seu PR e, se necessário, uma descrição mais detalhada do que foi feito.

Clique em Create pull request.

A partir daí, sua branch estará pronta para ser revisada pela equipe!
