# hash-tool

A simple commandline tool similar to shasum that but for a wide variety of non-cryptographic hashes.

## Installation

Install globally with npm or yarn:

```
npm install -g hash-tool
```

```
yarn global add hash-tool
```

## Usage

```
$ hash-tool -a farmhash32 /usr/share/dict/words /usr/share/dict/propernames
7c9f7e5a  /usr/share/dict/words
35e067fe  /usr/share/dict/propernames
```
