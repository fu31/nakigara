# nakigara
nakigara web site 

# Pre Installtion

- Install goenv  
`brew install goenv`   

- Install go and set the 1.11.4  
`goenv install 1.11.4`  
`goenv global 1.11.4`  

- set the path  
`export GO15VENDOREXPERIMENT=1`  
`export GOPATH=$HOME/go`  
`export PATH=$PATH:$GOPATH/bin`  
`export PATH=$PATH:$GOROOT/bin`  
`eval "$(goenv init -)"`

# Chimpo

# Installtion  

- Install beego  
`go get github.com/astaxie/beego`  
`go get github.com/beego/bee`  
- start beego  
# git clone
go $HOME/go/src and git clone
`git clone https://github.com/fu31/nakigara.git`
`bee run`  
- access root page  
http://localhost:8080/

see the this page more detail installtion  
https://qiita.com/macococo/items/e5ace2550418ccced9ac


see the this page more detail beego  
https://beego.me/



