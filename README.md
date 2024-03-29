## Prerequisites

1. PostgreSQL or MySQL if you choose to use a database.

1. Go programming language, version 1.3.x or newer.

1. Ensure `$GOPATH/bin` is in your `$PATH`. Example: `PATH=$PATH:$GOPATH/bin`



## Installation

1. `go get github.com/Tanmay-312/Go-DatabaseServer-WebApp`

1. `$GOPATH/bin/Go-DatabaseServer-WebApp -dir github.com/{git-user}/{project-name} -template {core|postgresql|mysql}`

1. Start using it: `cd $GOPATH/src/github.com/{git-user}/{project-name} && go run main.go`