# code-test

Director profile page with animated stickman SVG (`index.html`).

## Local preview

```powershell
cd C:\Users\user\Desktop\code-testt
node -e "const http=require('http'),fs=require('fs'),path=require('path');const r=process.cwd(),p=8765,m={'.html':'text/html'};http.createServer((q,s)=>{const f=path.join(r,q.url==='/'?'/index.html':q.url);fs.readFile(f,(e,d)=>{s.writeHead(e?404:200,{'Content-Type':m[path.extname(f)]||'text/plain'});s.end(e?'Not found':d);});}).listen(p,()=>console.log('http://127.0.0.1:'+p+'/'));"
```

Open [http://127.0.0.1:8765/](http://127.0.0.1:8765/) in the browser.
