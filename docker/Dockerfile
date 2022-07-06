FROM jupyter/scipy-notebook

ADD docker/requirements.txt .
RUN pip install -r requirements.txt

WORKDIR /home/jovyan/work

# docker build --tag school:1.0 --file docker/Dockerfile .
# docker run --detach --volume /home/susumu/school_analysis/notebooks:/home/jovyan/work --name school_container -p 8888:8888 school:1.0