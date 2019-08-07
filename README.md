&nbsp;
<p align="center">
<img alt="Liman Logo" src="https://raw.githubusercontent.com/salihciftci/liman/master/public/img/liman.png" width=200>
</p>

<h3 align="center">Liman</h3>
<p align="center">
Self-hosted web application for monitoring docker.
</p>
<p align="center">
<img alt="Docker Build Status" src="https://img.shields.io/docker/build/salihciftci/liman">
<img alt="GitHub release" src="https://img.shields.io/github/release/salihciftci/liman">
<img alt="GitHub" src="https://img.shields.io/github/license/salihciftci/liman">
</p>

----

&nbsp;
<p align="center">
<img src="https://user-images.githubusercontent.com/3863655/62650331-51633a80-b95f-11e9-850b-f5f4c5b1891e.png">
</p>

&nbsp;

----

&nbsp;
## Installation

[Download](https://github.com/salihciftci/liman/releases) and run the latest binary or ship with Docker.

```
$ docker volume create liman
$ docker run -it -v /var/run/docker.sock:/var/run/docker.sock -v liman:/liman/data salihciftci/liman
```

Note: the `-v /var/run/docker.sock:/var/run/docker.sock` option can be used in Linux environments only. 

## API Usage 
Examples and all end points can be found in [wiki](https://github.com/salihciftci/liman/wiki/API-Usage).

## Screenshots



||||
|:-------------:|:-------:|:-------:|
|![Containers](https://user-images.githubusercontent.com/3863655/62650329-50caa400-b95f-11e9-923a-d33fd77faa65.png)|![Stats](https://user-images.githubusercontent.com/3863655/62650333-51633a80-b95f-11e9-837e-6c37901f73f6.png)|![Images](https://user-images.githubusercontent.com/3863655/62650330-50caa400-b95f-11e9-878e-ad1bde3d30ec.png)|

## License
MIT