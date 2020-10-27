FROM continuumio/anaconda3

LABEL maintainer="<vasily.boychuk@t-systems.com>"

WORKDIR /home/vasily/Projects/rekko-challenge/notebooks

# execute
CMD ["jupyter",  "notebook",  "--notebook-dir=/home/vasily/Projects/rekko-challenge/notebooks",  "--ip=0.0.0.0",  "--allow-root", "--port=9990",  "--no-browser"]