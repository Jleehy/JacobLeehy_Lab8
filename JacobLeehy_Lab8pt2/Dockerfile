# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY NFL_Score.c .
# Compile the C program
RUN gcc -o NFL_Score NFL_Score.c
# Set the command to run when the container starts
CMD ["./NFL_Score"]