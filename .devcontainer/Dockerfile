FROM node

RUN npm install eslint typescript @angular/cli sass-lint -g

WORKDIR /holy-viewer

ENV LANG=C.UTF-8
ENV LANGUAGE=C.UTF-8
ENV LC_ALL=C.UTF-8
ENV TZ=America/Sao_Paulo
ENV DEBUG_COLORS=true
ENV FORCE_COLOR=true

EXPOSE 4907

# The run the start script
CMD [ "/bin/bash" ]
