# Big-Data-Analytics-Using-Spark-edX

Pull the Docker image

```console
docker pull ucsddse230/cse255-dse230
```

Run the Docker image

```console
docker run -it -p 8888:8888 -v "$(pwd):/home/ucsddse230/work" ucsddse230/cse255-dse230 /bin/bash
```

Then launch Jupyter Notebook inside the container

```console
jupyter notebook
```

Finally, open <http://localhost:8888> on a browser
