## Github CI CD

### 1. Generate ssh

```bash
cd ~/.ssh
ssh-keygen -f naura -N ""
```

### 2. Insert pubkey to authorized_keys

```bash
cat naura.pub >> authorized_keys
```

### 3. Copy private key to your github secret

```bash
cat naura
```
