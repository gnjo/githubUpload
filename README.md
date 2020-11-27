# githubUpload
Github.js util


```

let repourl="https://gnjo.github.io/githubUpload/"

let gu=githubUpload(token)
await gu.test(repourl) //exist dir check. true or false
await gu.test(repourl,file) //exist file check. true or false

await gu.write(repourl) //make dir
await gu.write(repourl,file,filedata) //make file 

await gu._delete(repourl) //delete dir !!!danger
await gu.delete(repourl,file) //delete file

await gu.read(repourl) //get filelist
await gu.read(repourl,file) //get file

is.base64data //data://...
is.base64 //ademlaei2222...
is.fileurl 

```
