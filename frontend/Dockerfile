# we need all functionallity from the golang
From golang:1.8.5

# his also instructs Docker to use this directory as the default destination for all subsequent commands. instead of writing the full command
WORKDIR /app 
COPY . .

# The next thing we need to do is to copy our source code into the image

RUN go build

#we then expose it to port 8000, but we can choose what we want.
EXPOSE 8080

#all that is left to do is to tell Docker what command to execute when our image is used to start a container.
CMD ["./frontend"]