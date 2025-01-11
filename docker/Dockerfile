FROM python:3.11

RUN useradd --home-dir /home/jenkins --create-home --shell /bin/bash --uid 1000 jenkins

USER jenkins

RUN pip install --upgrade pip

RUN pip install xmlrunner

RUN pip install unittest-xml-reporting

RUN pip install jinja2~=3.1.3 && \
    pip install numpy==1.24.3
