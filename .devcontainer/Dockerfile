ARG VARIANT=20.04
FROM mcr.microsoft.com/devcontainers/base:ubuntu-${VARIANT}

# RUN apt update \
#     && apt install -y python3 python3-pip clang-12 bear valgrind \
#     && python3 -m pip install --upgrade pip \
#     && python3 -m pip install pre-commit norminette

RUN apt update \
    && apt install -y clang-12 bear valgrind