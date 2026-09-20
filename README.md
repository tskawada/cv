# cv

## Verify CV signature

```
curl https://github.com/tskawada.gpg | gpg --import
curl -LO https://github.com/tskawada/cv/releases/latest/download/Yuta_Kawada_CV.pdf
curl -LO https://github.com/tskawada/cv/releases/latest/download/Yuta_Kawada_CV.pdf.asc
gpg --verify Yuta_Kawada_CV.pdf.asc Yuta_Kawada_CV.pdf
```
