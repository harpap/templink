# templink
apt-get update \
&& apt-get install -y software-properties-common curl \
&& add-apt-repository ppa:deadsnakes/ppa \
&& apt-get update \
&& apt-get install -y python3.6 python3.6-venv
