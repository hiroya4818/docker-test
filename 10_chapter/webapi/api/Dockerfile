FROM gradle:7

WORKDIR /api
COPY . .
RUN chmod +x gradlew

CMD [ "./gradlew", "bootRun" ]