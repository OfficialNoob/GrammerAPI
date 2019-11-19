# GrammerAPI (My code is bad)
A grammar fixer that uses AI to fix stuff  
POST raw data to https://grammarapi.herokuapp.com/  

Models download at the deepcorrect github  
Credit:
  https://github.com/bedapudi6788/deepcorrect
  https://github.com/bedapudi6788/deepsegment

How to use:
```
async function grammarapi(str) {
    let r = await fetch('https://grammarapi.herokuapp.com', {
        method: 'POST',
        body: str
    })
    return r.text();
}
```
