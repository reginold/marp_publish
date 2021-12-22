---
marp: true
---
# AWS EFS 関連技術
- [fstabについて](https://qiita.com/kihoair/items/03635447591358210772)
    - fstabの利用によりインスタンスのNFSマウントできる
     - `cat /etc/fstab`で詳細を編集 
---
# AWS Datasync 関連技術
- s3,efsなら、`aws sync xx xx` CLIでもよい
- オンプレなら、データをオンプレからs3に転送datasyncの方が良い
- Amazon S3 Glacier または Amazon S3 Glacier Deep Archive などの耐久性のある安全な長期ストレージに直接移動できる
