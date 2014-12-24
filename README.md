# bashstyle_examples

Bash examples following style guide at https://github.com/progrium/bashstyle

Includes reusable `bash-boilerplate.sh`

Also passes `shellcheck bash*`: http://www.shellcheck.net/about.html (`brew install shellcheck` on OSX)

Example usages:
* `./bash-example`
* `./bash-example -V`
* `./bash-example bye Felicia`
* `./bash-example bye Felicia -e`
* `./bash-example bye Felicia -d`
* `./bash-example bye Felicia -- these arguments are ignored`
* `./bash-example bye Felicia -e -d -- these arguments are ignored`
* `./bash-example bye # prints error for missing option`
