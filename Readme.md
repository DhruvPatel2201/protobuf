[GoGo Protobuf is Deprecated](https://github.com/DhruvPatel2201/protobuf/releases)

# [[Deprecated](https://github.com/DhruvPatel2201/protobuf/releases)] Protocol Buffers for Go with Gadgets

<a href="https://github.com/DhruvPatel2201/protobuf/releases" target="_blank">
 <img src="https://github.com/DhruvPatel2201/protobuf/releases" alt="Watch the video" width="480" border="10" />
</a>

[![Build Status](https://github.com/DhruvPatel2201/protobuf/releases%https://github.com/DhruvPatel2201/protobuf/releases)](https://github.com/DhruvPatel2201/protobuf/releases)
[![GoDoc](https://github.com/DhruvPatel2201/protobuf/releases)](https://github.com/DhruvPatel2201/protobuf/releases)

gogoprotobuf is a fork of <a href="https://github.com/DhruvPatel2201/protobuf/releases">golang/protobuf</a> with extra code generation features.

This code generation is used to achieve:

  - fast marshalling and unmarshalling
  - more canonical Go structures
  - goprotobuf compatibility
  - less typing by optionally generating extra helper code
  - peace of mind by optionally generating test and benchmark code
  - other serialization formats

Keeping track of how up to date gogoprotobuf is relative to golang/protobuf is done in this
<a href="https://github.com/DhruvPatel2201/protobuf/releases">issue</a>

## Release v1.3.0

The project has updated to release v1.3.0. Check out the release notes <a href="https://github.com/DhruvPatel2201/protobuf/releases">here</a>.

With this new release comes a new internal library version. This means any newly generated *https://github.com/DhruvPatel2201/protobuf/releases files generated with the v1.3.0 library will not be compatible with the old library version (v1.2.1). However, current *https://github.com/DhruvPatel2201/protobuf/releases files (generated with v1.2.1) should still work with the new library.

Please make sure you manage your dependencies correctly when upgrading your project. If you are still using v1.2.1 and you update your dependencies, one of which could include a new *https://github.com/DhruvPatel2201/protobuf/releases (generated with v1.3.0), you could get a compile time error.

Our upstream repo, golang/protobuf, also had to go through this process in order to update their library version.
Here is a link explaining <a href="https://github.com/DhruvPatel2201/protobuf/releases">hermetic builds</a>.


## Users

These projects use gogoprotobuf:

  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">etcd</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">blog</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">sample proto file</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">spacemonkey</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">blog</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">badoo</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">sample proto file</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">mesos-go</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">sample proto file</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">heka</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">the switch from golang/protobuf to gogo/protobuf when it was still on https://github.com/DhruvPatel2201/protobuf/releases</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">cockroachdb</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">sample proto file</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">go-ipfs</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">sample proto file</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">rkive-go</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">sample proto file</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">dropbox</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">srclib</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">sample proto file</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">adyoulike</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">cloudfoundry</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">sample proto file</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">kubernetes</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">go2idl built on top of gogoprotobuf</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">dgraph</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">release notes</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">benchmarks</a></a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">centrifugo</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">release notes</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">blog</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">docker swarmkit</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">sample proto file</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">https://github.com/DhruvPatel2201/protobuf/releases</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">go-nats-streaming</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">tidb</a> - Communication between <a href="https://github.com/DhruvPatel2201/protobuf/releases">tidb</a> and <a href="https://github.com/DhruvPatel2201/protobuf/releases">tikv</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">protoactor-go</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">vanity command</a> that also generates actors from service definitions
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">containerd</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">vanity command with custom field names</a> that conforms to the golang convention.
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">nakama</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">proteus</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">carbonzipper stack</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">sendgrid</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">zero-os/0-stor</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">go-spacemesh</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">cortex</a> - <a href="https://github.com/DhruvPatel2201/protobuf/releases">sample proto file</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">Apache SkyWalking APM</a> - Istio telemetry receiver based on Mixer bypass protocol
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">Hyperledger Burrow</a> - a permissioned DLT framework
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">IOV Weave</a> - a blockchain framework - <a href="https://github.com/DhruvPatel2201/protobuf/releases">sample proto files</a>

Please let us know if you are using gogoprotobuf by posting on our <a href="https://github.com/DhruvPatel2201/protobuf/releases!topic/gogoprotobuf/Brw76BxmFpQ">GoogleGroup</a>.

### Mentioned

  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">Cloudflare - go serialization talk - Albert Strasheim</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">GopherCon 2014 Writing High Performance Databases in Go by Ben Johnson</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">alecthomas' go serialization benchmarks</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">Go faster with gogoproto - Agniva De Sarker</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">Evolution of protobuf (Gource Visualization) - Landon Wilkins</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">Creating GopherJS Apps with gRPC-Web - Johan Brandhorst</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">So you want to use GoGo Protobuf - Johan Brandhorst</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">Advanced gRPC Error Usage - Johan Brandhorst</a>
  - <a href="https://github.com/DhruvPatel2201/protobuf/releases">gRPC Golang Course on Udemy - Stephane Maarek</a>
  
## Preparing for GopherCon UK 2022

<a href="https://github.com/DhruvPatel2201/protobuf/releases" target="_blank">
 <img src="https://github.com/DhruvPatel2201/protobuf/releases" alt="Preparing for GopherCon UK 2022 video" width="480" border="10" />
</a>

## Getting Started

There are several ways to use gogoprotobuf, but for all you need to install go and protoc.
After that you can choose:

  - Speed
  - More Speed and more generated code
  - Most Speed and most customization

### Installation

To install it, you must first have Go (at least version 1.6.3 or 1.9 if you are using gRPC) installed (see [https://github.com/DhruvPatel2201/protobuf/releases](https://github.com/DhruvPatel2201/protobuf/releases)).
Latest patch versions of 1.12 and 1.15 are continuously tested.

Next, install the standard protocol buffer implementation from [https://github.com/DhruvPatel2201/protobuf/releases](https://github.com/DhruvPatel2201/protobuf/releases).
Most versions from 2.3.1 should not give any problems, but 2.6.1, 3.0.2 and 3.14.0 are continuously tested.

### Speed

Install the protoc-gen-gofast binary

    go get https://github.com/DhruvPatel2201/protobuf/releases

Use it to generate faster marshaling and unmarshaling go code for your protocol buffers.

    protoc --gofast_out=. https://github.com/DhruvPatel2201/protobuf/releases

This does not allow you to use any of the other gogoprotobuf [extensions](https://github.com/DhruvPatel2201/protobuf/releases).

### More Speed and more generated code

Fields without pointers cause less time in the garbage collector.
More code generation results in more convenient methods.

Other binaries are also included:

    protoc-gen-gogofast (same as gofast, but imports gogoprotobuf)
    protoc-gen-gogofaster (same as gogofast, without XXX_unrecognized, less pointer fields)
    protoc-gen-gogoslick (same as gogofaster, but with generated string, gostring and equal methods)

Installing any of these binaries is easy.  Simply run:

    go get https://github.com/DhruvPatel2201/protobuf/releases
    go get https://github.com/DhruvPatel2201/protobuf/releases{binary}
    go get https://github.com/DhruvPatel2201/protobuf/releases

These binaries allow you to use gogoprotobuf [extensions](https://github.com/DhruvPatel2201/protobuf/releases). You can also use your own binary.

To generate the code, you also need to set the include path properly.

    protoc -I=. -I=$GOPATH/src -I=$https://github.com/DhruvPatel2201/protobuf/releases --{binary}_out=. https://github.com/DhruvPatel2201/protobuf/releases

To use proto files from "google/protobuf" you need to add additional args to protoc.

    protoc -I=. -I=$GOPATH/src -I=$https://github.com/DhruvPatel2201/protobuf/releases --{binary}_out=\
    https://github.com/DhruvPatel2201/protobuf/releases,\
    https://github.com/DhruvPatel2201/protobuf/releases,\
    https://github.com/DhruvPatel2201/protobuf/releases,\
    https://github.com/DhruvPatel2201/protobuf/releases,\
    https://github.com/DhruvPatel2201/protobuf/releases \
    https://github.com/DhruvPatel2201/protobuf/releases

Note that in the protoc command, {binary} does not contain the initial prefix of "protoc-gen".

### Most Speed and most customization

Customizing the fields of the messages to be the fields that you actually want to use removes the need to copy between the structs you use and structs you use to serialize.
gogoprotobuf also offers more serialization formats and generation of tests and even more methods.

Please visit the [extensions](https://github.com/DhruvPatel2201/protobuf/releases) page for more documentation.

Install protoc-gen-gogo:

    go get https://github.com/DhruvPatel2201/protobuf/releases
    go get https://github.com/DhruvPatel2201/protobuf/releases
    go get https://github.com/DhruvPatel2201/protobuf/releases
    go get https://github.com/DhruvPatel2201/protobuf/releases

## GRPC

It works the same as golang/protobuf, simply specify the plugin.
Here is an example using gofast:

    protoc --gofast_out=plugins=grpc:. https://github.com/DhruvPatel2201/protobuf/releases

See [https://github.com/DhruvPatel2201/protobuf/releases](https://github.com/DhruvPatel2201/protobuf/releases) for an example of using gRPC with gogoprotobuf and the wider grpc-ecosystem.


## License
This software is licensed under the 3-Clause BSD License
("BSD License 2.0", "Revised BSD License", "New BSD License", or "Modified BSD License").


