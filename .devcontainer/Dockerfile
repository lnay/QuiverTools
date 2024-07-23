FROM docker.io/sagemath/sagemath:10.3

RUN mkdir -p /tmp/quivertools/
COPY setup.py /tmp/quivertools/setup.py
COPY quiver /tmp/quivertools/quiver
RUN sage --pip install /tmp/quivertools/