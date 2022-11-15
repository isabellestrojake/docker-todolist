FROM mjgargani/puppeteer:trybe1.0 AS todotests

ADD node_modules.tar.gz /dk-ts

COPY . /dk-ts

ENTRYPOINT ["npm", "test"] 