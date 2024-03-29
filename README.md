# cloud-fundamentals

1. [Storage & Content Delivery](#schema1)
2. [AWS Management](#schema2)


<hr>
<a name='schema1'></a>

## 1. Storage & Content Delivery

Create a NoSQL Database

https://aws.amazon.com/es/getting-started/hands-on/create-nosql-table/


Create a MySQL Database

https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html

Aurora

https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html

Download and install the MySQL Workbench on your local computer.

https://dev.mysql.com/downloads/workbench/



CloudFront:


Amazon CloudFront es un servicio de red de entrega de contenido (CDN) proporcionado por Amazon Web Services (AWS). 
Una CDN es una red de servidores distribuidos globalmente que trabaja para acelerar la entrega de contenido web, 
como imágenes, videos, hojas de estilo y otros recursos, a los usuarios finales. CloudFront ayuda a reducir la 
latencia al almacenar en caché contenido en ubicaciones estratégicas (llamadas puntos de presencia) alrededor del mundo.


https://aws.amazon.com/es/cloudfront/

https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html



<hr>
<a name='schema2'></a>

## 2. AWS Management



Install or update the latest version of the AWS CLI

https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

Ver la version del cli

```
aws --version
```


Para ver las instancias EC2 que se estan ejecutando

```
aws ec2 describe-instances
```