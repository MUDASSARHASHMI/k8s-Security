# Without any analysis
FROM alpine:latest

USER root
COPY sunnydale.sh .

USER root
CMD ["./sunnydale.sh"]

---
# After analysis
FROM alpine:3.13.5

USER root
COPY sunnydale.sh .

USER nobody
CMD ["./sunnydale.sh"]