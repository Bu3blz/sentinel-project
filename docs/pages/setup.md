### Setup

#### Requirements

- To clone the repository: [git](https://git-scm.com/downloads) (CLI)
- To compile the source files: [GO](https://go.dev/doc/install) (>=1.23.0)

#### Download, compile, and execute with a single command

- on Linux:
```bash
project="sdakit-project";exe="sdakit";cmd="./build/Linux/build.sh";git clone "https://github.com/PlagueByteSec/$project.git" && cd $project && chmod +x $cmd && $cmd && ./bin/$exe
```

#### Setup Manually

- Clone the sdakit repository (Windows, Linux)

```
git clone https://github.com/PlagueByteSec/sdakit-project.git
```

#### Build the source files into a executable, and display the available options

- on Linux:
```bash
cmd="./build/Linux/build.sh";chmod +x $cmd && $cmd
```

- on Windows:
```
.\build\Windows\build.bat && .\bin\sdakit.exe
```

<div align="center">
<a href="https://plaguebytesec.github.io/sdakit-project">Home</a>
</div>