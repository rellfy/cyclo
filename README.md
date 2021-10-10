# cyclo
Encyclopedia system using LaTeX and Rust

## Running
From the root directory, build the `texlive` image:
```
sudo docker build -t texlive -f docker/texlive docker
```
Then, build and run the `cyclo` image:
```
sudo docker build -t cyclo -f docker/cyclo docker
sudo docker run cyclo
```
