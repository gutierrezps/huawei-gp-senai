# Huawei GP SENAI

Olá. Nesta página você pode ter acesso às informações atualizadas do desafio Huawei do Grand Prix SENAI de Inovação.

**Última atualização**: 2022-10-19 10h40

## Desafio

Atualmente, as empresas que possuem suas redes locais demandam muitos investimentos com atualização de software, manutenção da rede, e com equipes especializadas. Nesse cenário, a computação em nuvem vem sendo usada cada vez mais em diferentes aplicações, seja para redução desses custos, escalabilidade, confiabilidade, segurança, disponibilidade, rápida implementação etc. É um ótimo ambiente inclusive pensando na implantação de um site, por exemplo, e na Huawei Cloud esse processo pode ser feito por meio da plataforma CCE (Cloud Container Engine), um serviço de alto desempenho e alta confiabilidade no qual as empresas podem gerenciar aplicações conteinerizadas.

Neste desafio, sua equipe terá que implementar um site de uma empresa fictícia em um container da Huawei Cloud, baseando-se em duas plataformas já consolidadas: WordPress e phpBB. Tal site deverá ter as seguintes características:

1.	Apresentação da empresa (utilize a plataforma WordPress para isso):
    1. Página de apresentação da empresa, mostrando um pouco da história dela e sua área de atuação
    2.	Catálogo de produtos, com uma página para cada produto, mostrando suas características
    3.	Página com dados de contato da empresa, mostrando seu endereço, telefone e e-mail
2.	Plataforma de fórum para interação entre a empresa e seus clientes (utilize a plataforma phpBB para isso):
    1. Um subfórum para cada produto da empresa
    2. Dentro de cada subfórum, crie um tópico fixado com as características de cada produto
    3. Simule o uso do fórum: crie dois usuários que serão os funcionários da empresa (administradores do fórum), e que deverão criar os subfóruns e e tópicos; crie outros dois usuários que serão os clientes da empresa, criando tópicos com dúvidas de cada produto que devem ser respondidas pelos usuários administradores
 
As equipes (todos os membros) que tiverem um progresso de, no mínimo, 5% do curso de Python ganharão dois pontos como complemento, seguindo os seguintes passos:
1.	Acessar a Plataforma Huawei TALENT
2.	Criar um Login Huawei usando material de apoio e guias
3.	Associar-se ao SENAI DN (Mandatório)
4.	Entrar na turma criada para Python no SENAI DN: Código JkYSvc

### Vá além: ideias para se diferenciar

- Melhore a segurança do seu container: altere as senhas de acesso SSH (PuTTY) e do banco de dados
- Defina um esquema de cores para sua empresa (ex: azuis, verdes, vermelhos)
- Personalize o WordPress com o esquema de cores escolhido
- Altere o tema do WordPress e do phpBB
- Adicione imagens nas páginas dos seus produtos e no fórum (use um serviço de hospedagem de imagens)
- Nas páginas dos produtos, adicione os links para os subfóruns, e vice versa
- Ajuste o arquivo `/var/www/html/index.html` de forma que contenha os links tanto para o WordPress quanto para o phpBB

## Materiais para inscrição na plataforma Huawei Talent

<https://drive.google.com/drive/folders/1FaiZl5vvWk2I3D47uI5jP4mAFMFhzgPt?hl=pt-BR>

## Tutorial de instalação do WordPress

<https://huawei-gp-senai.obs.sa-brazil-1.myhuaweicloud.com/WordPress%20v2.0.pdf>

## Tutorial de instalação do phpBB

Baseando-se no tutorial de instalação do WordPress, instale o phpBB:

1. Baixe o arquivo zip do phpBB: <https://www.phpbb.com/>
2. Descompacte o arquivo zip baixado na pasta `/var/www/html` (utilize a ferramenta `unzip`)
3. Altere as permissões da pasta do phpBB3 (comando `chmod`)
4. Acesse o link `http://<endereço IP da sua equipe>:8###/phpBB3` e siga o processo de instalação (pode ignorar a mensagem "`[phpBB Debug] "chmod(): Operation not permitted"`")
5. Ao final, remova a pasta "install" de dentro do phpBB3

## Lista de equipes

Veja no link a seguir o código de três dígitos que identifica sua equipe (**ATENÇÃO: confira o Estado e o Autor**) e o endereço IP a ser utilizado:

<https://huawei-gp-senai.obs.sa-brazil-1.myhuaweicloud.com/Identifica%C3%A7%C3%A3o%20Equipes.pdf>

## Registro de mudanças

- 2022-10-19 10h40 - Correção do percentual mínimo de progresso no curso de Python
- 2022-10-19 01h30 - Adicionadas ideias para se diferenciar, tutorial de instalação do phpBB e lista de equipes
- 2022-10-18 16h30 - Publicação do desafio, materiais para inscrição na plataforma Huawei Talent e tutorial de instalação do WordPress
- 2022-10-18 11h10 - Versão inicial
