FROM mjgargani/puppeteer:trybe1.0

ADD ./node_modules.tar.gz .

WORKDIR /app

COPY . .

ENTRYPOINT [ "npm" ]

CMD [ "test" ]