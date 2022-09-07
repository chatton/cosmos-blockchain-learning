# Building a Cosmos Blockchain

### Install Ignite CLI

```bash
curl https://get.ignite.com/cli@v0.22.2! | sudo bash

which ignite # /usr/local/bin/ignite
```


Create a Cosmos Blockchain called `hello`

```bash
ignite scaffold chain hello
```

Start the chain locally

```bash
cd hello
ignite chain server
```

Create a new message type

```bash
ignite scaffold query hello --response text
```
