FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html

# docker build -t dath1/deployment:1.0 .

# docker push dath1/deployment:1.0

# then run the 17-deployment-service.yaml to tets the deployment

# Test with url http://<LB_DNS_NAME>:80

# change the verion in index.html and build the image again to  test the deployment

# docker build -t dath1/deployment:2.0 .

# docker push dath1/deployment:2.0