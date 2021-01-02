# BoostimQuickStart
A QuickStart project for Boostim. \
Boostim is a set of solutions for instant messaging.

## Related Repositories
- [BoostimCenter](https://github.com/teimichael/BoostimCenter): center node (controller)
- [BoostimNode](https://github.com/teimichael/BoostimNode): common node (worker)
- [BoostimAuth](https://github.com/teimichael/BoostimAuth): authentication system
- [BoostimWebClient](https://github.com/teimichael/BoostimWebClient): easy-integration web client

## Port
- BoostimAuth: 9500
- BoostimAuthMySQL: 9501
- BoostimCenter: 9510
- BoostimNode: 9511
- BoostimDataMySQL: 9600

## Command
### Pull third containers
```bash
chmod u+x ./pull3rdContainers.sh
./pull3rdContainers.sh
```

### Pull projects from GitHub
```bash
chmod u+x ./cloneRepositories.sh
./cloneRepositories.sh
```

### Start up projects
```bash
docker-compose up
```

#### Deamon mod
```bash
docker-compose up -d
```

### Shut down projects
```bash
docker-compose down
```

#### Shut down and clear projects
```bash
docker-compose down --rmi 'all'
```