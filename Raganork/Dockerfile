FROM souravkl11/raganork:test

RUN git clone https://github.com/aflahq/Mark2/ /skl/mark2
WORKDIR /skl/mark2 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "raganork.js"]
