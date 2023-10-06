How to build an image

Run the following command, replace the value for -t as you need

docker build -t mydockercity/dotnet-runtime:net6-alpine -f Dockerfile-NET6-Runtime-Alpine .

docker build -t mydockercity/dotnet-runtime:net7-alpine -f Dockerfile-NET7-Runtime-Alpine .

To publish an image:

docker push mydockercity/netruntime:net7-alpine

To search for images by repo:

docker image ls mydockercity/netruntime