# Reason Proto

## add
```shell
# normal add
git submodule add -b master --name api/auth-proto https://github.com/go-cinch/auth-proto.git ./api/auth-proto

# or force add
git submodule add -f -b master --name api/auth-proto https://github.com/go-cinch/auth-proto.git ./api/auth-proto
```

## update
```shell
git submodule update --force --recursive --init --remote
```
