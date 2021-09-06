# Useful Linux commands

## Create directory

```bash
mkdir [dirname]
```

## Copy folder
```bash
cp -R <source_folder> <destination_folder>
```

## Get list of users login to current host

```bash
users
```

## Create user

Creates user without home dir and etc:
```bash
sudo useradd [username]
```

Creates user with home dir and etc:
```bash
sudo adduser [username]
```

## Get list of groups a user is in
```bash
groups
```

## Add new group

```bash
sudo addgroup [groupname]
```

## Add user to group

```bash
sudo adduser [username] [groupname]
```

## Delete user from group

```bash
sudo deluser [username] [groupname]
```

## Print the groups a user is in


```bash
sudo groups [username]
```

## Create file

```bash
touch [filename]
```

## File content

```bash
cat [filename]
```

## Search in file 
```bash
grep [search] [filename]
```

## Edit file
```bash
vi [filename]
```

```bash
vim [filename]
```

```bash
nano [filename]
```

## File and folder permissions

```bash

chmod [user][usergroup][all] [filename-or-foldername]

```
[read][write][execute]

|#  | binary | rwx|
|:--|:---    |:---|
|0  |000     |--- |
|1  |001     |--x |
|2  |010     |-w- |
|3  |011     |-wx |
|4  |100     |r-- |
|5  |101     |r-x |
|6  |110     |rw- |
|7  |111     |rwx |

## Change owner

```bash
chown [newownuser]
```

## Create custom shortcut

```bash
alias ll="ls -la"
```

## Other commands

```bash
sudo login [username]
```

```bash
logout
```

### Connecting via SSH to your server

```bash
ssh [username]@[server_ip]
```

### Display IP of all devices

```bash
ip a
```

### Shutdown linux machine immediately

```bash
sudo shutdown now
```
### Upload folder to VPS

```bash
scp -r user@ssh.example.com:/path/to/remote/source /path/to/local/destination
```
