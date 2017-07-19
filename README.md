# anaconda3-ubuntu
anaconda3 in ubuntu 16.04.

* 実行
  - cpu
    ```
    $ docker run --init -it shimtom/anaconda3:latest
    ```
  - gpu
    ```
    $ nvidia-docker run --init -it shimtom/anaconda3:latest-gpu
    ```
