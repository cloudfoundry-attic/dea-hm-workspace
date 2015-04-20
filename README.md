# HM Workspace

[![Build Status](https://travis-ci.org/cloudfoundry/hm-workspace.png)](https://travis-ci.org/cloudfoundry/hm-workspace)

A Go workspace for specifiying dependencies for [HM9000](http://github.com/cloudfoundry/hm9000).

## Usage
1. Dependencies:
     Install `direnv` using your package manager, e.g. `brew install direnv` on MacOs using homebrew. This will automatically set `GOPATH` and `PATH` when you enter the folder.
2. Clone the HM-workspace:

         $ cd $HOME
         $ git clone https://github.com/cloudfoundry/hm-workspace
         $ cd hm-workspace
         $ git submodule update --init
