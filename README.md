# app_tasks
Reforçando php orientado a objetos e bootstrap 

É necessario o uso do XAMPP ou um programa de sua preferencia (que faça os requests e respostas da propria maquina) para rodar a aplicação.
Após a instalação, separe a pasta publica (app_lista_tarefas_public) da pasta privada(app_lista_tarefas) para que a segurança da aplicação permaneça intacta.
-Adicione a pasta publica no diretoria publico da sua maquina e a pasta privada no diretorio privado(será explicado em breve).
-Não se esqueça de ajustar os 'requires' no incio dos arquivos para que o script entenda onde estao os scripts requeridos.

Caso deseje rodas a aplicação em um servidor com banco de dados proprio fora da maquina, adicione as informações na classe 'Class Conexao' em sua instancia 'conectar()'. 

APÓS ABRIR O XAMPP Control Panel->
Inicie o Apache e o MySql.
A pasta public deve ir no seguinte endereço-> 'C:\xampp\htdocs\app_lista_tarefas_public'
A pasta privada deve ir no seguinte endereço-> 'C:\xampp\app_lista_tarefas'
Após as etapas acima entre no 'localhost/phpmyadmin' em seu browser e crie uma base de dados que vai ser usada para a gravação dos dados (verifique se o nome esta de acordo com os scripts para evitar erros).


________________________________________________________________________________________________________________________________________________________________________________________________________________

Strengthening object-oriented PHP and Bootstrap

It is necessary to use XAMPP or a program of your choice (that makes requests and responses from your own machine) to run the application. 
After installation, separate the public folder (app_lista_tarefas_public) from the private folder (app_lista_tarefas) so that the security of the application remains intact. 
Add the public folder to the public directory of your machine and the private folder to the private directory (this will be explained soon). 
Don’t forget to adjust the ‘requires’ at the beginning of the files so that the script understands where the required scripts are.

If you want to run the application on a server with its own database outside of the machine, add the information in the ‘Class Conexao’ class in its ‘conectar()’ instance.

AFTER OPENING THE XAMPP Control Panel -> 
Start Apache and MySql. 
The public folder should go to the following address -> ‘C:\xampp\htdocs\app_lista_tarefas_public’. 
The private folder should go to the following address -> ‘C:\xampp\app_lista_tarefas’. 
After completing the above steps, enter ‘localhost/phpmyadmin’ in your browser and create a database that will be used for data recording (make sure the name is in accordance with the scripts to avoid errors).


__________________________________________________________________________________________________________________________________________________________________________________________________________________
@julliox
