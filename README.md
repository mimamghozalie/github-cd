## Github CI CD

### 1. Generate ssh

```bash
cd ~/.ssh
ssh-keygen -f chizu -N ""
```

### 2. add pubkey to authorized_keys

```bash
cat chizu.pub >> authorized_keys
```

### 3. Copy private key to your github secret

```bash
cat chizu
```
