# DynamoDB - AWS Associate Curso.
Aqui você encontrará os arquivos para a aula do Professor André Iacono,  referente ao curso de Associate na Udemy.

## Comando para clonar
```
sudo git clone https://github.com/FtxDante/dynamodb
```

## Arquivos da Aula
Aqui você encontrará os arquivos para a aula do Professor André Iacono, referente ao curso de Associate na Udemy.

```
#!/bin/bash
yum update -y
yum install httpd php git -y
service httpd start
chkconfig httpd on
cd /var/www/html
echo "<?php phpinfo();?>" > home.php
git clone <https://github.com/andreiacono/dynamodb>

```

O código acima é um script em bash que instala e configura o servidor web Apache (httpd) em uma instância Amazon Linux.

A seguir, segue uma explicação linha por linha do código:

1. `#!/bin/bash`: Especifica que o script deve ser executado com o interpretador de comandos bash.
2. `yum update -y`: Atualiza todos os pacotes da instância Amazon Linux.
3. `yum install httpd php git -y`: Instala o servidor web Apache, a linguagem de programação PHP e o sistema de controle de versão Git.
4. `service httpd start`: Inicia o servidor web Apache.
5. `chkconfig httpd on`: Configura o servidor web Apache para ser iniciado automaticamente na inicialização da instância.
6. `cd /var/www/html`: Navega até o diretório em que os arquivos da página web serão armazenados.
7. `echo "<?php phpinfo();?>" > home.php`: Cria um arquivo PHP com o conteúdo `<?php phpinfo(); ?>` chamado `home.php`.
8. `git clone <https://github.com/andreiacono/dynamodb>`: Clona o repositório GitHub do projeto DynamoDB na instância Amazon Linux.
