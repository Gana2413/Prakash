# Use Nginx to serve static site
FROM nginx:alpine

# Copy index.html to Nginx web root
COPY index.html /usr/share/nginx/html/index.html

# Copy resume PDF to Nginx web root
COPY Prakash.P_Devopsengineer_Resume.pdf /usr/share/nginx/html/

# (Optional) Copy images folder if you have any
COPY images/ /usr/share/nginx/html/images/
