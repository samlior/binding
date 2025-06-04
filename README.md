# Binding

C++ binding for rei network

## Dependences

- `boost` 1.78.0
- `rei-network/evmone` 0.9
- `rei-network/evmc` 10.0.0
- `rei-network/leveldb` 1.25
- `napi-macros` 2.0.0
- `snappy` 1.1.9

## Install

```
npm i @rei-network/binding
```

## Recommended tool version

- `clang` 13.0.1 or `gcc` 8.5.0
- `cmake` 3.20.5

## Build

```
git clone https://github.com/REI-Network/binding
git submodule update --init --recursive
npm install
npm run build
npm run build:tsc
```

## Test

```
npm run test
```

## License

GPL-3.0-or-later
