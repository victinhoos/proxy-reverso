<p align="center">
  <img width="250" height="250" alt="Image" src="https://github.com/user-attachments/assets/a461b227-8bb4-4169-88ac-2a57b5ef55ce" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-CONCLUÍDO-brightgreen?style=for-the-badge" alt="Status Concluído" />
</p>

![Badge Nginx](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Badge PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)


## Objetivo

Projeto desenvolvido para demonstrar como distribuir requisições HTTP entre múltiplos servidores, evitando concentrar todo o tráfego em uma única instância. Utiliza NGINX como proxy reverso e balanceador de carga, Docker para isolamento dos serviços e Docker Compose para orquestração da infraestrutura, explorando conceitos de escalabilidade horizontal e arquitetura distribuída.

## Como funciona?

O Nginx atua como servidor web, recebendo requisições HTTP e direcionando-as para o PHP. O PHP processa a lógica da aplicação no servidor e gera as respostas dinâmicas. O Nginx encaminha os scripts PHP para o PHP-FPM, responsável por executá-los.Após o processamento, a resposta retorna ao Nginx, que a entrega ao cliente. Essa arquitetura permite separar as responsabilidades e melhorar a eficiência da aplicação.