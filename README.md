# bob-walker

An alternative to [alphagov/vcloud-walker](https://github.com/alphagov/vcloud-walker). Implemented in Bash and Go and Perl and Awk.

## Usage

### Awk

```sh
awk -f bob-walker.awk [-v sport=true]
```

### Bash

```sh
./bob-walker.sh
```

### Brainf--k (using [this python interpreter](https://github.com/garretraziel/mindfuck))

```
# Normal mode
echo "0" | ../mindfuck/mindfuck.py bob-walker.fk
# Sport mode!
echo "1" | ../mindfuck/mindfuck.py bob-walker.fk
```

### C

```sh
# To compile
gcc -o bob-walker bob-walker.c
# Normal mode
./bob-walker
# Sport mode!
BOB_MODE=SPORT ./bob-walker
```

### Go

```sh
go run bob-walker.go
```

### Perl

```perl
./bob-walker.pl
```
