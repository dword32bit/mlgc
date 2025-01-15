# Gunakan image Nginx sebagai server web
FROM nginx:alpine

# Salin semua file ke direktori default Nginx
COPY . /usr/share/nginx/html

# Nginx secara default akan melayani file dari /usr/share/nginx/html
EXPOSE 80

# Jalankan Nginx saat container dimulai
CMD ["nginx", "-g", "daemon off;"]
