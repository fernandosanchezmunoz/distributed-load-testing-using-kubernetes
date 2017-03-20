FROM frolvlad/alpine-python2
EXPOSE 80
ADD . app.py 
RUN touch index.html
RUN apk --update add py-netifaces --update-cache --repository http://dl-3.alpinelinux.org/alpine/edge/testing/
RUN pip install webapp2
CMD python app.py
