#使うDockerイメージ
FROM openjdk:8u252-jdk
#アップデート
RUN apt-get update
# gradleインストール
RUN apt-get -y install curl
RUN apt-get -y install zip
RUN curl -s "https://get.sdkman.io" | bash
RUN echo ". $HOME/.sdkman/bin/sdkman-init.sh; sdk install gradle" | bash
# ワーキングディレクトリの設定
WORKDIR /usr/src