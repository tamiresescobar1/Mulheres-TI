Contribuições

Contribua no diretório "Community", criando um Profile README contendo informações sobre você que deseje compartilhar com a comunidade.
Para isso, você pode inserir: badges indicando suas habilidades; cards com suas estatísticas no GitHub e projetos que criou, colaborou ou que deseje que outras pessoas colaborem.
Além disso, você pode inserir também links para seus desafios de projeto e artigos.
Inspire-se consultando os exemplos na pasta community, confira alguns utilitários na pasta utils e use sua criatividade para criar o seu 😊💙.

Instruções (PT/BR)
Faça um Fork deste repositório;

![App Screenshot](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/028749c3-7110-479a-9de5-3a6222cd8966)

![App Screenshot](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/df03a6d3-a92b-4014-bd73-cc8c7c062024)

Não precisa alterar o nome ou a descrição, certifique-se de deixar seleciona a cópia da branch e aperte create fork!
Logo após já irá gerar o fork e será criado no seu usuário, ele aparecerá conforme imagem onde tem a opção da contribuição que veremos mais para frente:

![App Screenshot](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/629f9812-a77f-486b-918e-5afdc46a754b)

O próximo passo é criar o clone na nossa máquina, para que possa estar fazendo as alterações e enviando:

Clonar localmente:

![fork github4](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/defdca7a-32e3-4d2e-82a3-9a2bca8c035d)

Após realizar a cópia que pode ser tanto por https ou ssh, no exemplo foi por https. Voce irá abrir o GIT Bash e adicionar o `git clone + https://github.com/SEU_USERNAME/mulheres-ti`;

![git clone](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/239d9180-a6f9-426d-9ac0-ca0261f8f38d)

Adicione o remote upstream para manter seu repositório local atualizado. Por exemplo: `git remote add upstream https://github.com/tamiresescobar1/Mulheres-TI`;
Utilize o comando `git pull upstream main` para baixar e mesclar as alterações no seu repositório local com base na branch main deste repositório original de onde você fez o fork.
O que estamos fazendo é estar atualizando o repositorio local diretamente pelo git a partir do repositorio original do fork. Sem precisar primeiro estar atualizando repositorio remoto no github para em seguida estar baixando no repositorio local!

![git clone2](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/f4c8feec-b48d-4fb2-9ce7-72bd44296e56)

Disto isso com tudo atualizado, já podemos estar criando uma nova branch, que é nosso próximo passo :)

Crie/Referêncie uma nova branch e nomeie como feat/community/SEU_USERNAME: `git checkout -b feat/community/nome que queira dar para pasta (que faça sentido);
Exemplo: git checkout -b feat/community/frontend-passo-a-passo/

![git markdown](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/555db9e8-14b5-47a4-8586-5d6ecd71d4de)

Nessa parte, voce pode criar o arquivo mesmo pelo terminal/computador ou continuar pelo git (se atente passar o nome sempre na pasta community)

Dentro da pasta community, crie um arquivo em Markdown (extensão .md) e nomeie com o mesmo nome do seu usuário no GitHub;
Exemplo: links.md

Nessa parte, voce pode perceber que toda alteração/criação que fizer, já está ligada ao terminal/computador.

![clone](https://github.com/tamiresescobar1/Mulheres-TI/assets/124881009/f81c500b-4a38-4fbf-856e-84880679a900)

Aqui pode já abrir o arquivo no terminal pelo bloco de notas e fazer a alteração. (criar o passo a passo, adicionar links ...) 
USE E ABUSE da sua criatividade.

Adicione suas alterações a "staging area" com o comando git add community/SEU_USERNAME.md;
Crie um commit e adicione a mensagem indicando a adição do seu perfil git commit -m"feat: add SEU_USERNAME profile";
Envie as alterações para o seu repositório remoto git push origin feat/community/SEU_USERNAME;
Crie um Pull Request.
