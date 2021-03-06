# Weaveworks Tools

Included in this repo are tools shared by weave.git and scope.git.  They include

- ```cover```: a tool which merges overlapping coverage reports generated by go test
- ```lint```: a script to lint Go project; runs various tools like golint, go vet, errcheck etc
- ```rebuild-image```: a script to rebuild docker images when their input files change; useful
  when you using docker images to build your software, but you don't want to build the
  image every time.
- ```socks```: a simple, dockerised SOCKS proxy for getting your laptop onto the Weave network
- ```test```: a script to run all go unit tests in subdirectories, gather the coverage results,
  and merge them into a single report.
