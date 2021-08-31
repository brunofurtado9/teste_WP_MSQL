# teste_WP_MSQL
Teste WordPress DockerFile

### Construção do Projeto:

Como nunca mexi com essa tecnologia tive que realizar pesquisas sobre o assunto, segue abaixo as minhas tentativas e o que consegui fazer.

Tentei procurar dicas e sites para entender o DockerFile mas ao ler o código não consegui executar.
- https://github.com/onnimonni/alpine-wordpress/blob/master/Dockerfile

Encontrei alguns sites para realizar a instalação do Docker Compose no Debian usando o VirtualBox e o programa Putty para acessar via SSH:

- https://www.edivaldobrito.com.br/tecnologia-docker-no-debian/
- https://qastack.com.br/programming/14494747/add-images-to-readme-md-on-github - Site que usei para aprender a inserir as imagens no Github.

Utilizei o site abaixo para pegar algumas dicas de formatação no Github:

- https://docs.github.com/pt/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

Como informei na entrevista não possuo conhecimento em Docker, então fui me baseando em pesquisas no Google e peguei o código ".yml" pronto no site abaixo, como também consegui validar a configuração do WordPress no Debian.
- https://www.hostinger.com.br/tutoriais/como-instalar-wordpress-no-docker-windows-macos-e-linux

Realizei a configuração no Debian e consegui levantar o container para realizar a configuração do WordPress.

![alt text](https://raw.githubusercontent.com/brunofurtado9/teste_WP_MSQL/main/screenshots/1%20-%20Instalando%20o%20WordPress.jpg) Instalação do WordPress.

![alt text](https://raw.githubusercontent.com/brunofurtado9/teste_WP_MSQL/main/screenshots/2%20-%20Configurando%20a%20inicializa%C3%A7%C3%A3o%20do%20WordPress.jpg) Configurando a inicialização do WordPress.

![alt text](https://raw.githubusercontent.com/brunofurtado9/teste_WP_MSQL/main/screenshots/3%20-%20Gerenciador%20WordPress.jpg) Gerenciador do WordPress.

![alt text](https://raw.githubusercontent.com/brunofurtado9/teste_WP_MSQL/main/screenshots/4%20-%20Acesso%20ao%20site%20do%20WordPress%20via%20IP.jpg) Acesso ao site do WordPress via IP.

![alt text](https://raw.githubusercontent.com/brunofurtado9/teste_WP_MSQL/main/screenshots/5%20-%20Iniciando%20o%20WordPress%2BMYSQL%20pelo%20docker-compose.jpg) Iniciando o WordPress+MYSQL pelo docker-compose utilizando o comando "up" para subir o container e o "-d" foi utilizado para levantar em background.

![alt text](https://raw.githubusercontent.com/brunofurtado9/teste_WP_MSQL/main/screenshots/6%20-%20Containers%20em%20Execu%C3%A7%C3%A3o.jpg) Containers em Execução. Utilizado o comando "ps" para listar os processos em execução, na imagem vemos que será acessado na porta 8000 e será redirecionado para a porta 80.

![alt text](https://raw.githubusercontent.com/brunofurtado9/teste_WP_MSQL/main/screenshots/7%20-%20Not%C3%ADcia%201%20no%20WordPress.jpg) Notícia 1 foi inserida no Blog de Notícias do WordPress.

![alt text](https://raw.githubusercontent.com/brunofurtado9/teste_WP_MSQL/main/screenshots/8%20-%20Not%C3%ADcia%202%20no%20WordPress.jpg) Notícia 2 foi inserida no Blog de Notícias do WordPress.

![alt text](https://raw.githubusercontent.com/brunofurtado9/teste_WP_MSQL/main/screenshots/9%20-%20Not%C3%ADcia%203%20no%20WordPress.jpg) Notícia 3 foi inserida no Blog de Notícias do WordPress.

