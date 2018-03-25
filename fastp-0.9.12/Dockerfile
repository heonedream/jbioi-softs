FROM kongdeju/alpine-dev
MAINTAINER kongdeju <kongdeju@gene.ac>
# install fastp by conda
RUN conda install -y fastp && conda clean -y --all
ADD fastp2table.py /opt/
