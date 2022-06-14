FROM ubuntu:jammy

LABEL mantainer="Fabio"

SHELL ["/bin/bash", "-xo", "pipefail", "-c"]

RUN apt update && apt upgrade -y && apt install -y curl nano wget git htop

CMD ["bin/bash"]
