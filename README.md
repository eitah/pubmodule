# Pubmodule

To install a private git module 
1. Add this to your git config usually at ~/.gitconfig
  [url "ssh://git@github.com/spantree-tempuslabs/"]
  insteadOf = https://github.com/spantree-tempuslabs/

1. then in your env export GOPRIVATE so that go knows not to check public module sources for it.
  export GOPRIVATE=github.com/spantree-tempuslabs
  
(omit spantree- as a prefix to the private module if doing tempus)

1. go get github.com/spantree-tempuslabs/mysecret... or just go run main.go 


## References

The content for this module is at https://www.digitalocean.com/community/tutorials/how-to-use-a-private-go-module-in-your-own-project
