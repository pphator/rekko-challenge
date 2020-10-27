FROM continuumio/anaconda3

LABEL maintainer="<vasily.boychuk@t-systems.com>"

WORKDIR /notebooks

# execute
CMD ["jupyter",  "notebook",  "--notebook-dir=/notebooks",  "--ip=0.0.0.0",  "--allow-root", "--port=9990",  "--no-browser"]