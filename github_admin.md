gh auth login

gh repo list <your-username> --limit 100 --json name --jq '.[].name'

gh auth refresh -h github.com -s delete_repo

gh repo delete helloram007/xls-js --yes

