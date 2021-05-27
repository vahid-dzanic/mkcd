# mkcd
Make a new directory and change to the newly created directory with one shell command

## How to use

```shell
~ $ mkcd some/directory/name

~/some/directory/name $ _
```

## How to install

Download the repository
```bash
git clone https://github.com/vahid-dzanic/mkcd.git
```
Copy the file mkcd into ```/usr/local/bin``` folder 
```bash
sudo cp mkcd/mkcd /usr/local/bin
```
Make sure ```/usr/local/bin``` is in the ```$PATH``` variable, otherwise you can add following to your ```.bashrc``` file:
```bash
export PATH=/usr/local/bin:$PATH
```

## How it works

```mkcd``` makes the directory similar to ```mkdir -p```, than it changes to the newly created directory and than it starts a new shell within this directory.
