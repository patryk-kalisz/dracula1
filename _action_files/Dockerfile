FROM fastai/jekyll:2020-12-30

WORKDIR /dracula
COPY . .
RUN chmod u+x action_entrypoint.sh
RUN chmod u+x word2post.sh
RUN dos2unix /dracula/*.sh

CMD [ "/dracula/action_entrypoint.sh" ]
