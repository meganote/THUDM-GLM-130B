ARG BASE_IMAGE=nvcr.io/nvidia/pytorch:23.02-py3

FROM ${BASE_IMAGE}

RUN pip install \
    -i https://pypi.tuna.tsinghua.edu.cn/simple --proxy="http://172.22.17.74:3928" \
    SwissArmyTransformer>=0.2.12 \
    icetk \
    apex \
    scipy \
    dataclass_wizard \
    cpm_kernels \
    bminf
