# Dzikri


```sh
go get -u all
go mod tidy
git tag                                 #check current version
git tag v1.0.0                          #set tag version
git push origin --tags                  #push tag version to repo
go list -m github.com/Dzikri7/BE-Geo@v1.0.0   #publish to pkg dev, replace ORG/URL with your repo URL