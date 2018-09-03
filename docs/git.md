git
---

### Create SSH keay for github

Open terminal

```bash
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

Then when complete

```bash
cat ~/.ssh/id_rsa.pub
```

copy contents and go to www GitHub.
