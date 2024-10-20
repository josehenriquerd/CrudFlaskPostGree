# CrudFlask

O proposito desse código foi criar um Crud utilizando um banco de dados, Python com a biblioteca Flask e rodar ele em um docker

Ao iniciar o projeto, ele abrirá da seguinte forma:
![image](https://github.com/user-attachments/assets/68161e4e-7353-4ddd-b461-785ad4814b37)

Funcionamento de Adição:
![image](https://github.com/user-attachments/assets/2bb9de73-2c2b-47c0-90d9-29d5b02c2624)

Funcionamento de Edição:
![image](https://github.com/user-attachments/assets/02da9b50-d555-46a9-a249-2d485f55dec7)
![image](https://github.com/user-attachments/assets/8735aabd-19b9-4612-bac8-96fc640f21d6)

DockerFile:
![image](https://github.com/user-attachments/assets/daa65c96-73ac-417e-8e72-85e6f58542a5)

DockerCompose:
![image](https://github.com/user-attachments/assets/80182d1c-9e9b-415a-856c-22d54d164450)


Comandos para gerar o build e rodar o docker:

Ao baixar o repositorio, abrir o cmd e ir até o diretorio onde a pasta foi baixada, ele deve ficar:

![image](https://github.com/user-attachments/assets/8e9f0e24-3137-4f50-bb20-d7db9a160757)

Ao estar nesse diretorio, rodar:
<code>
docker-compose up --build
</code>

Após rodar esse build, já pode abrir o docker:
<code>
http://127.0.0.1:5000/
</code>


