# pedia
Encyclopedia system using LaTeX and Rust

## Running
From the root directory, build the `texlive` image:
```
sudo docker build -t texlive -f docker/texlive docker
```
Then, build and run the `pedia` image:
```
sudo docker build -t pedia -f docker/pedia docker
sudo docker run pedia
```
