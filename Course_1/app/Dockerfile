# Complete the file :)

# Description :
FROM node:latest

# Explain :
RUN apk add --no-cache python2 g++ make

# Explain :
WORKDIR /app

# Description :
COPY . .

# Explain :
RUN yarn install --production

# Explain :
CMD ["node", "src/index.js"]
