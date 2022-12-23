FROM python:3
RUN apt-get update
RUN apt-get -y install locales \
    && localedef -f UTF-8 -i ja_JP ja_JP.UTF-8
ENV LANG ja_JP.UTF-8
ENV LANGUAGE ja_JP:ja
ENV LC_ALL ja_JP.UTF-8
ENV TZ JST-9
RUN apt-get update
RUN apt-get -y install graphviz
RUN pip install --upgrade pip
RUN pip install jupyter
RUN pip install numpy
RUN pip install matplotlib==3.5.2
RUN pip install pandas
RUN pip install scipy
RUN pip install scikit-learn
RUN pip install mglearn
RUN pip install graphviz
RUN pip install sympy