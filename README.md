# Tch_lab6

-- Logowanie na docker huba --

docker login

![logowanie](https://user-images.githubusercontent.com/129669781/232244032-4f200ae2-8652-4fc9-a779-f856fc7dc0d6.png)

-- Budowa obrazu --

DOCKER_BUILDKIT=1 docker build -t manotiwak/lab6:v1 .

![budowa_obrazu](https://user-images.githubusercontent.com/129669781/232244457-aa534560-b884-4163-b42d-5c00860e34c7.png)

-- Przesłanie obrazu na docker huba --

docker push manotiwak/lab6:v1

![przesłanie_obrazu](https://user-images.githubusercontent.com/129669781/232244570-926f261f-06d7-411c-954f-a4e2884340fb.png)
