FROM alpine:3.18.4
COPY . .
RUN apk add curl

#CMD [ "./mill -w app.runBackground" ]
ENTRYPOINT ["./mill", "-w", "app.runBackground"]

