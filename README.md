1. Install revive: `go install github.com/mgechev/revive@latest`
2. Verify that revive doesn't throw an error about upper-case constants through the local linter: `revive -config revive.toml`
3. Check GitHub to see if the `golangci-lint` action threw an error about upper-case constants