# Contribuições

Contribua no diretório "Community", criando um Profile README contendo informações sobre você que deseje compartilhar com a comunidade.
Para isso, você pode inserir: cards com suas estatísticas no GitHub e projetos que criou, colaborou ou que deseje que outras pessoas colaborem.
Além disso, você pode inserir também links para seus desafios de projeto e artigos.
Inspire-se consultando os exemplos na pasta community, confira alguns utilitários na pasta utils e use sua criatividade para criar o seu 😊💙.

Instruções (PT/BR):

Faça um Fork deste repositório;

![fork github](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/1cf252ec-1ae8-4538-b01c-58126b11988d)

Não precisa alterar o nome ou a descrição, certifique-se de deixar selecionado a cópia da branch e aperte create fork!

![fork github2](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/7db681bc-8b21-419d-8fc1-9ee7ed1d65f1)

Logo após já irá gerar o fork e será criado no seu usuário, ele aparecerá conforme imagem onde tem a opção da contribuição que veremos mais para frente:

![fork github3](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/f029eead-ff04-4c9f-b9fc-b39a60a1a921)

O próximo passo é criar o clone na nossa máquina, para que possa estar fazendo as alterações e enviando:

# Clonar localmente:

![fork github4](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/2319a21b-1fe8-4882-a67a-2561d0b772d6)

- Após realizar a cópia que pode ser tanto por https ou ssh, no exemplo foi por https. Voce irá abrir o GIT Bash e adicionar o `git clone + https://github.com/SEU_USERNAME/mulheres-ti`;

![git clone](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/f2f2150b-7f38-4341-bc57-53a8358a3317)

Adicione o remote upstream para manter seu repositório local atualizado. Por exemplo: `git remote add upstream https://github.com/tamiresescobar1/Mulheres-TI`;
Utilize o comando `git pull upstream main` para baixar e mesclar as alterações no seu repositório local com base na branch main deste repositório original de onde você fez o fork.
O que estamos fazendo é estar atualizando o repositorio local diretamente pelo git a partir do repositorio original do fork. Sem precisar primeiro estar atualizando repositorio remoto no github para em seguida estar baixando no repositorio local!

![git clone2](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/34ad62e6-2156-4247-a6be-e536ca1957ce)

Disto isso com tudo atualizado, já podemos estar criando uma nova branch, que é nosso próximo passo :)

Crie/Referêncie uma nova branch e nomeie como feat/community/SEU_USERNAME: `git checkout -b feat/community/nome que queira dar para pasta (que faça sentido);
Exemplo: git checkout -b feat/community/frontend-passo-a-passo/

![git markdown](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/6421da74-9114-44f6-80f2-ad960a5f6da9)

Nessa parte, voce pode criar o arquivo mesmo pelo terminal/computador ou continuar pelo git (se atente passar o nome sempre na pasta community)

Dentro da pasta community, crie um arquivo em Markdown (extensão .md) e nomeie com o mesmo nome do seu usuário no GitHub;
Exemplo: links.md

Nessa parte, voce pode perceber que toda alteração/criação que fizer, já está ligada ao terminal/computador.

![clone](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/db266560-f122-41fa-b5bb-b2d2315b2506)

Aqui pode já abrir o arquivo no terminal pelo bloco de notas e fazer a alteração. (criar o passo a passo, adicionar links ...) 
USE E ABUSE da sua criatividade.

Finalizado as alterações, no git de um comando `git status`, irá aparecer os arquivos que ainda não estão adicionados, logo adicione suas alterações a "staging area" com o comando `git add community/nome criado anteriormente`;

Para finalizar digite novamente o comando `git status` e verá que o arquivo já foi adicionado, chegou o momento de deixa registrado sua commit.
Crie um commit e adicione a mensagem indicando a adição do seu perfil `git commit -m "feat: add SEU_USERNAME profile"`;

![git clone3](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/d735232f-68a4-44b9-8a43-2d639a2da501)

Envie as alterações para o seu repositório remoto `git push origin feat/community/SEU_USERNAME`;

![git clone4](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/4c08edba-bc10-4f11-9969-e46f54e60034)

Crie um Pull Request.
