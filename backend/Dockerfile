# we need all functionallity from the golang
From golang:1.8.5

# his also instructs Docker to use this directory as the default destination for all subsequent commands. instead of writing the full command
WORKDIR /app 

#But before we can run go mod download inside our image, we need to get our go.mod and go.sum files copied into it
COPY go.mod ./
COPY go.sum ./
RUN go mod download

# The next thing we need to do is to copy our source code into the image
COPY *.go ./
RUN go build

#we then expose it to port 9000, but we can choose what we want.
EXPOSE 9000

#all that is left to do is to tell Docker what command to execute when our image is used to start a container.
CMD ["./backend"]

