

# Preparar entorno de desarrollo NativeScript 5.4

    git clone git@github.com:diegonella/meemba-docker-native54.git
    cd meemba-docker-native54
    docker build -t meemba-docker-native54 ./
    cd cd nativescript_app
    docker run -it --rm -v $(pwd):/app meemba-docker-native54 bash -C "tns --version"

