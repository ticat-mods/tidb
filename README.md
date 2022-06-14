# TiDB on ticat

## Installing (All platform)
```
curl --proto '=https' --tlsv1.2 -sSf https://raw.githubusercontent.com/ticat-mods/tidb/main/install.sh | sh
```

## Installing (CentOS)
The script depends on `git`, install it first:
```
sudo yum install -y git epel && && sudo yum upgrade -y && curl --proto '=https' --tlsv1.2 -sSf https://raw.githubusercontent.com/ticat-mods/tidb/main/install.sh | sh
```
