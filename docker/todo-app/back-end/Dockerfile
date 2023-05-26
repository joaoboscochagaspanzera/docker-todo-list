FROM node:16-alpine
WORKDIR /app/back-end
COPY . .
EXPOSE 3001
ENTRYPOINT [ "npm" ]
CMD ["start"]
ADD node_modules.tar.gz .