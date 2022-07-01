# Pubmodule

Add this to your git config usually at ~/.gitconfig
  [url "ssh://git@github.com/tempuslabs/"]
  insteadOf = https://github.com/tempuslabs/

(add spantree- as a prefix to the private module)

then in your env do
╰─➤  export GOPRIVATE=github.com/spantree-tempuslabs

so that go knows not to check public module sources for it.