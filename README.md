# centos7-setup
Setup script for CentOS7 with Docker

## Usage

### 1. Login to your host as root

```
(Local) $ ssh root@<host>
```

### 2. Create setup script

```
$ vi setup

(Paste the content of "setup")
```

### 3. Grant execution permission to the script

```
$ chmod u+x setup
```

### 4. Run the script

```
$ ./setup
```

### 5. Register public key of login user

```
$ vi /home/<username>/.ssh/authorized_keys

(Paste public key of <username>)
```

### 6. Confirm the login user can login

```
(Local) $ ssh <username>@<host>
```

DONE
