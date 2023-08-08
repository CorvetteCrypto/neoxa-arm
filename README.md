# neoxa-arm
This is a ARM64 distribution of the NeoxaChain/Neoxa project compiled on a Raspberry Pi 4B

Options used to compile and link:
  with wallet         = no
  with gui / qt       = no
  with zmq            = no
  with test           = no
  with bench          = no
  with upnp           = yes
  use asm             = yes
  sanitizers          =
  debug enabled       = no
  stacktraces enabled = yes
  crash hooks enabled = no
  miner enabled       = yes
  gprof enabled       = no
  werror              = no
  target os           = linux
  build os            =
  CC                  = gcc
  CFLAGS              = -pthread -pipe -O2  -g1 -fno-omit-frame-pointer
  CPPFLAGS            = -I[REMOVED]  -DHAVE_BUILD_INFO -D__STDC_FORMAT_MACROS
  CXX                 = g++ -std=c++14
  CXXFLAGS            = -pipe -static-libstdc++ -O2  -g1 -fno-omit-frame-pointer
  LDFLAGS             = -lpthread -L[REMOVED]
  ARFLAGS             = cr
