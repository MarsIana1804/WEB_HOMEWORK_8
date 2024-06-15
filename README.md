TASK 1

pip install mongoengine

python -m pip install "pymongo[srv]"==3.11

pip install pymongo mongoengine

TASK 2

pip install pika

docker pull rabbitmq


docker run -d --hostname my-rabbit --name some-rabbit -p 5672:5672 -p 8080:15672 -e RABBITMQ_DEFAULT_USER=marina_adm -e RABBITMQ_DEFAULT_PASS=rabit_qwerty rabbitmq:3-management
