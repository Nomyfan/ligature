# ligature

Patch ligatures to your favorite font.

Create the `task.py` file in the root filling the content like [task-example.py](./tasks-example.py)

## Run

### Ubuntu 20.04 LTS

```
sudo apt-get update
sudo apt-get install python3-fontforge
```

## Build
After editing [task.py](./tasks.py)
```
mkdir output && python3 ./build.py
```