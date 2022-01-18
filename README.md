# Repro for issue with NAPI.rs build

## Steps to reproduce

1. `yarn install`
2. `yarn repro_ok` - this should print "hello!"
3. `yarn repro_nok` - this should fail with `TypeError: require(...).test is not a function`
