# Use a imagem oficial do NGINX como base
FROM nginx:alpine

# Copie os arquivos de configuração personalizados para dentro do contêiner
COPY nginx.conf /etc/nginx/nginx.conf
COPY site1 /usr/share/nginx/html/site1
COPY site2 /usr/share/nginx/html/site2

# Exponha as portas 80 e 8080
EXPOSE 8181
EXPOSE 8282