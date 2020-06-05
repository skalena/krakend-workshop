FROM devopsfaith/krakend

COPY krakend.json /etc/krakend/krakend.json

ENTRYPOINT [ "/usr/bin/krakend" ]
CMD [ "run", "-c", "/etc/krakend/krakend.json"]
