# sumit

A simple commandline tool similar to shasum that but for a wide variety of non-cryptographic hashes.

## Installation

Install globally with npm or yarn:

```
npm install -g sumit
```

```
yarn global add sumit
```

## Usage

```
$ sumit -a farmhash32 /usr/share/dict/words /usr/share/dict/propernames
7c9f7e5a  /usr/share/dict/words
35e067fe  /usr/share/dict/propernames
```
