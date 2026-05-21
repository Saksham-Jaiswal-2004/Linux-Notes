## Chapter 7: File Transfer Commands

1. scp - to send files from local device to cloud/server, ex. scp -i {private key file path} {filename} {server address}

2. scp -i {private key file path} -r {server address with file path} {destination in local device}
   -> -r - is used for directories/folders, i.e., recursive copy of all files in that folder

3. rsync - to sync remote and local folders