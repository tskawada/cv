## Verify CV signature

```bash
curl https://github.com/YOUR_USERNAME.gpg | gpg --import
gpg --verify cv.pdf.asc cv.pdf
```
