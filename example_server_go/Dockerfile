FROM debian:stable-slim

# copy source dst
COPY learn_go /bin/learn_go

# Set PORT environment variable
ENV PORT=8080

# run server on image startup
CMD ["/bin/learn_go"]
