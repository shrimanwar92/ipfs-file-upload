# ipfs-file-upload

1) Install IPFS on your platform https://dist.ipfs.io/#go-ipfs

2) If on local set CORS  
 a) ipfs config --json API.HTTPHeaders.Access-Control-Allow-Origin "[\"http://example.com\"]"  
 b) ipfs config --json API.HTTPHeaders.Access-Control-Allow-Credentials "[\"true\"]"  
 c) ipfs config --json API.HTTPHeaders.Access-Control-Allow-Methods "[\"PUT\", \"POST\", \"GET\"]"  

3) ipfs init

4) ipfs daemon

5) Then start server
For ex. python -m SimpleHTTPServer 1337
