# douyin a_bogus

使用方式
```
userAgent = 'your agent'
url = 'request url'
headers={
#headers
}
abogus = execjs.compile(open("bogus.js", 'r', encoding='utf-8').read()).call('getBogus', url, '', userAgent)
url = url + '&a_bogus=' + xbogus
resp = requests.get(url, headers=headers)
```
