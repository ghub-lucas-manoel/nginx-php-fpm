# nginx-php-fpm
Desafio Inovadora

Segue os arquivos para criação de uma página php que retorna dado em json para um servidor em xginx, distribuídos em container utilizando Docker e docker-compose.

O sistema foi desenvolvido baseado em vídeos no YouTube e a documentação das ferramentas utilizadas.

Após a implementação do código e alguns testes, o sistema começou a apresentar uns erros de execução (o php estava fechand com exit code 64 e o nginx com exit code 0).
Foi necessário rebuildar os serviços utlizando docker-compose build para que os problemas não retornassem a acontecer novamente.

Para um melhor entendimento dos comandos, foi estudado o básico de nginx. Apesar de não ter aprendido algumas diretivas, os comandos básico e preceitos do nginx
foram entendidos.
