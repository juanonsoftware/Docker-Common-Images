How to build an image

Run the following command, replace the value for -t as you need

docker build -t mydockercity/dotnet-runtime:net-v6.0.22-alpine -f Dockerfile-NET6-Runtime-Alpine .

docker build -t mydockercity/dotnet-runtime:net-v7.0.11-alpine -f Dockerfile-NET7-Runtime-Alpine .

docker build -t mydockercity/dotnet-runtime:sdk-net7-alpine-231008 -f Dockerfile-NET7-SDK-Alpine .

docker build -t mydockercity/dotnet-runtime:sdk-net6-alpine-latest -f Dockerfile-NET6-SDK-Alpine .

To publish an image:

docker push mydockercity/netruntime:net7-alpine

To search for images by repo:

docker image ls mydockercity/netruntime