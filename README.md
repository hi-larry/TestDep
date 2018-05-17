# TestDep
Testing dependencies

# Comparing behaviours

**Manually updating package.json** 
(in branch _manually_)
1. `cd LCS`
2. Update ioredis from `^2.5.0` to `^3.2.2`
3. In a terminal, run `npm install --package-lock-only`

**Updating package.json using the command** 
(in branch _command-only_)
1. `cd LCS`
2. In a terminal, run `npm install ioredis@3.2.2 --package-lock-only`


Compare both package-lock.json files.
